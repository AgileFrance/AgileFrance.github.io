---
permalink: /
---

# À propos de l’association

L’association Agile France se donne pour but de soutenir financièrement, administrativement, logistiquement, organisationnellement, communicationnellement, nutritionnellement et psychologiquement des actions visant à promouvoir de près ou de loin les méthodes agiles de développement logiciel, sous toutes formes et pour tous publics, de préférence francophones.

# Demander à être soutenu

Une initiative soutenue par l'association bénéficie librement du [matériel](/inventaire) commun.

## [Rejoindre l'association](adhesion)

# Soutiens récents

## 2018

- [Conférence Agile France](https://2018.conf.agile-france.org)
- [Agile Open France](http://agileopenfrance.com/)
- [Meetup OPEN Nouvelle-Calédonie](https://www.meetup.com/fr-FR/Meetup-des-professionnels-du-numerique-en-Nouvelle-Caledonie/events/252426773/)
- [Meetup Systémique et agilité](https://www.meetup.com/fr-FR/Systemique-Agilite-dialogue-pour-transformer-lentreprise/)

## 2017

- [Conférence Agile France](https://2017.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/810a24b6-2765-400b-aacc-da609cec39be-agile-open-france-2017-aof17.html)
- [Comparatif de post-its](https://medium.com/@MattiSG/stupid-science-i-compared-23-sticky-notes-to-help-you-spare-wallet-and-planet-fc9b97d88503)

## 2016

- [Conférence Agile France](https://2016.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/61f3f1b3-9ad7-4c40-b5ca-6316b134853f-agile-open-france-2016-aof16.html)
- [Geek Camp](https://www.meetup.com/fr-FR/software-craftsmanship-bdx/events/230739321)

## 2015

- [Conférence Agile France](https://2015.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/c4513d61-5d3b-4996-8fa2-2d76462a7c52-agile-open-france-2015-aof15.html)

## 2014

- [Conférence Agile France](https://2014.conf.agile-france.org)
- Agile Open France
- Geek Camp
- Agile Beirut
- Lean Camp


# Le mot de l’asso

Lors de la conférence AgileFrance a régulièrement eu lieu une prise de parole de l’association. Ces « mots » font partie de son histoire publique.

{% assign mots = site.mot_conference | reverse %}

{% for mot in mots -%}
- [{{ mot.title }}]({{ mot.url }})
{% endfor %}


# Assemblées générales

Les assemblées générales sont les réunions annuelles lors desquelles le bureau présente son bilan, où le bureau peut être renouvelé, et où de grandes orientations peuvent être décidées.

{% assign assemblees_generales = site.assemblee_generale | reverse %}

{% for ag in assemblees_generales -%}
- [{{ ag.title }}]({{ ag.url }})
{% endfor %}


# Bureaux

Le bureau de l’association est actuellement composé de :

- [Matti Schneider](https://mattischneider.fr/)
- [Peggy Avez](http://peggyavez.com/)
- [Julien Porot](https://linkedin.com/in/julienporot)
- [Émilie Esposito](https://linkedin.com/in/emilie-esposito)
- [David Larlet](https://larlet.fr/david/)

Les bureaux successifs ont donné des orientations à l’association qui ont construit son histoire.

{% assign bureaux = site.bureau | reverse %}

{% for bureau in bureaux -%}
- {{ bureau.election | date: "%Y" }} — [{{ bureau.title }}]({{ bureau.url }})
{% endfor %}


# Documents

- [Statuts](/statuts)
- [Réglement intérieur](/reglement)
