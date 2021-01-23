Le site de l'association Agile France
=====================================

## Développement

Ce site est construit avec [Jekyll](https://jekyllrb.com/), un générateur de sites statiques. La version utilisée est celle [actuellement en production](https://pages.github.com/versions/) sur GitHub Pages.

Pour l'améliorer, installer [Ruby](https://www.ruby-lang.org/fr/) et [Jekyll](https://jekyllrb.com) dans leurs [versions de production](https://pages.github.com/versions/) :

```sh
git clone https://github.com/AgileFrance/AgileFrance.github.io.git
cd AgileFrance.github.io
gem install bundler --no-ri --no-rdoc
bundle install
bundle exec jekyll serve
```

Dans l'éventualité où l'installation de `nokogiri` poserait problème avec les versions système de `libxml`, vous pouvez tenter d'installer [rbenv](https://github.com/rbenv/rbenv) en combinant une nouvelle installation avec la variable d'environnement `NOKOGIRI_USE_SYSTEM_LIBRARIES` mise à `true`.

Les fichiers pertinents pour une modification de la présentation sont probablement dans les dossiers `_layouts` et `css`.


## Déploiement

La mise en production est faite via [GitHub Pages](https://pages.github.com). Il suffit de pousser sur la branche `master` pour déployer sur `agilefrance.github.io`.

Le domaine `agile-france.org` est configuré pour pointer vers GitHub Pages, qui lit le fichier `CNAME` de ce dépôt pour servir le contenu déployé sur `agilefrance.github.io`.
