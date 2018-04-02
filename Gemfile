require 'json'
require 'net/http'

source 'https://rubygems.org'

begin
  versions_url = URI('https://pages.github.com/versions.json')
  versions     = JSON.parse(Net::HTTP.get(versions_url))

  # Make sure we build locally with the same version than Github Pages does.
  gem 'github-pages', versions['github-pages'], group: :jekyll_plugins

# If the GitHub Pages versions endpoint is unreacheable, we assume offline development.
rescue SocketError => socket_error
  puts <<-MESSAGE
    Couldn't reach #{versions_url.to_s}, assuming you're offline.
  MESSAGE

  # Use whichever version is already installed without checking production version match.
  gem 'github-pages'

# If for any other reason the production versions check fails, we still provide a fallback scenario.
rescue => standard_error
  puts <<-MESSAGE
    Something went wrong trying to parse production versions.
      Exception name:    #{standard_error.class.name}
      Exception message: #{standard_error.message}
  MESSAGE

  # Try to use whatever version is already installed.
  gem 'github-pages'
end
