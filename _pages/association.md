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

- [Fabrice Bloch](https://fr.linkedin.com/in/fabrice-bloch-4b9b5194)
- [Gwendoline Cartier](https://www.linkedin.com/in/gwendoline-c-25b93229/)
- [Yannis Martin](https://www.linkedin.com/in/yannismartin/)
- [Pierre Grigoletto](https://www.linkedin.com/in/pierre-grigoletto/)  
- [Natacha Fourmy](https://www.linkedin.com/in/natacha-fourmy/)

Les bureaux successifs ont donné des orientations à l’association qui ont construit son histoire.

{% assign bureaux = site.bureau | reverse %}

{% for bureau in bureaux -%}
- {{ bureau.election | date: "%Y" }} — [{{ bureau.title }}]({{ bureau.url }})
{% endfor %}

## États généraux

Le bureau a organisé en janvier 2022 des « [États généraux](/etats-generaux-2022) », une série d'ateliers pour penser ensemble le futur d'Agile France.

## Le mot de l’asso

Lors de la conférence AgileFrance a régulièrement eu lieu une prise de parole de l’association. Ces « mots » font partie de son histoire publique.

{% assign mots = site.mot_conference | reverse %}

{% for mot in mots -%}
- [{{ mot.title }}]({{ mot.url }})
{% endfor %}
