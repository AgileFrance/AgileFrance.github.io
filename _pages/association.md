---
title: Vie associative
permalink: /association
---

## Documents officiels

La vie de l'association est encadrée par ses [statuts](/statuts) et son [réglement intérieur](/reglement).


## Assemblées générales

Les assemblées générales sont les réunions annuelles lors desquelles le bureau présente son bilan, où le bureau peut être renouvelé, et où de grandes orientations peuvent être décidées.

{% assign assemblees_generales = site.assemblee_generale | reverse %}

{% for ag in assemblees_generales -%}
- [{{ ag.title }}]({{ ag.url }})
{% endfor %}


## Bureaux

Le bureau de l’association est actuellement composé de :

- [Matti Schneider](https://mattischneider.fr/)
- Julien Porot
- [Julie Quillé](https://www.linkedin.com/in/juliequille/)
- [Christophe Robillard](https://twitter.com/krichtof)
- Bénédicte Taillebois

Les bureaux successifs ont donné des orientations à l’association qui ont construit son histoire.

{% assign bureaux = site.bureau | reverse %}

{% for bureau in bureaux -%}
- {{ bureau.election | date: "%Y" }} — [{{ bureau.title }}]({{ bureau.url }})
{% endfor %}


## Le mot de l’asso

Lors de la conférence AgileFrance a régulièrement eu lieu une prise de parole de l’association. Ces « mots » font partie de son histoire publique.

{% assign mots = site.mot_conference | reverse %}

{% for mot in mots -%}
- [{{ mot.title }}]({{ mot.url }})
{% endfor %}
