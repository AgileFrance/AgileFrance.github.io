Le site de l'association Agile France
=====================================

## Développement

Ce site est construit avec [Jekyll](https://jekyllrb.com/), un générateur de sites statiques. La version utilisée est celle [actuellement en production](https://pages.github.com/versions/) sur GitHub Pages.

Pour l'améliorer, installer [Ruby](https://www.ruby-lang.org/fr/) et [Jekyll](https://jekyllrb.com) dans leurs [versions de production](https://pages.github.com/versions/) :

```sh
git clone https://github.com/betagouv/beta.gouv.fr.git
cd beta.gouv.fr
gem install bundler --no-ri --no-rdoc
bundle install
bundle exec jekyll serve
```

Les fichiers pertinents pour une modification de la présentation sont probablement dans les dossiers `_layouts` et `css`.


## Déploiement

La mise en production est faite via [GitHub Pages](https://pages.github.com). Il suffit de pousser sur la branche `master` pour déployer sur `agilefrance.github.io`.

Le domaine `agile-france.org` est configuré pour pointer vers GitHub Pages, qui lit le fichier `CNAME` de ce dépôt pour servir le contenu déployé sur `agilefrance.github.io`.
