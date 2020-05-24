---
permalink: /
---

## À propos de l’association

> L’association Agile France soutient la communauté agile francophone dans ses efforts pour faire évoluer la société vers plus d’efficacité, d’excellence, et de respect de tous les individus.
>
> L’association adhère aux quatre valeurs et aux douze principes énoncés dans le [Manifeste agile](https://agilemanifesto.org/iso/fr/manifesto.html).
>
> Pour cela, l’association entreprend et soutient toutes actions de promotion, de diffusion et d’éducation ayant trait aux concepts et pratiques dites agiles ; elle intervient également pour favoriser l’évolution professionnelle des personnes utilisant ces pratiques.

— _Article 2 des [Statuts de l’association](/statuts)_

## Appel à projets COVID-19

Cet [appel vise à produire du contenu et des outils qui facilitent l'adaptation au confinement](appel-a-projets-covid-19) et est doté de 10 000 € TTC.

## Notre mode d’action

Notre mode de soutien principal consiste en :

1. **Une prise en charge de la complexité administrative.** Nous mettons à disposition une association loi 1901 déjà constituée, domiciliée et immatriculée, un compte bancaire, et des assurances adaptées à la réalisation d’événements.
2. **Une mise à disposition de trésorerie jusqu’à 50k€.** On parle ici d’une avance potentiellement non remboursable en cas d’échec et non de subvention.
3. **Un accès à du [matériel mutualisé](/inventaire).**
4. **Un accès à des outils techniques de gestion d’événement** qui ont fait leurs preuves, et du conseil fourni par les équipes d’organisation des autres initiatives soutenues par l’association.
5. **Des subventions pour des billets** visant des publics défavorisés ou sous-représentés.

En contrepartie, nous nous attendons à ce que :

1. **Au moins un‧e des membres de l’équipe d’organisation soit [membre de l’association](adhesion)**, notamment afin de garantir l’application des contrats d’assurance.
2. **L’initiative ne soit pas conçue pour être déficitaire** (sinon, il s’agit d’une demande de subvention, que nous offrons plus exceptionnellement).
3. **Le public visé soit mixte et divers**, et plus généralement que l’événement soit inclusif. Nous vous enverrons notamment un sondage à adresser aux participant‧e‧s afin de pouvoir suivre cet aspect.
4. **L’organisation soit communautaire, sans sponsors commerciaux.**
5. **La majorité du contenu soit francophone.**
6. **Un rapport financier public soit fourni à l’issue du projet.** Il s’agit simplement de deux camemberts qui indiquent d’où viennent vos rentrées d’argent, et quelles sont vos dépenses. [Exemple](http://2017.conf.agile-france.org/docs/bilan-agilefrance-2017.pdf).
7. **Les éventuels bénéfices soient mutualisés**, ou que vous les utilisiez pour pérenniser votre initiative de manière indépendante.

Cela vous intéresse ? [Proposez votre initiative](mailto:bureau@agile-france.org?subject=Soutien) !

Vous n’êtes pas certain‧e d’être éligible mais votre initiative est compatible avec nos [statuts](/statuts) et vous vous sentez aligné‧e avec les [intentions du bureau](/bureau/2018) ? [Discutons-en](mailto:bureau@agile-france.org?subject=Demande) ! 😉


## Adhérer

Si vous partagez [nos valeurs](/bureau/2018) et que vous souhaitez soutenir nos efforts, [rejoignez l'association](adhesion) !

La cotisation annuelle coûte 20 €. En adhérant, vous obtenez accès à nos outils de prise de décision collective et donnez du poids aux initiatives soutenues.


## Initiatives soutenues

### 2020

- [Conférence Agile France](https://2020.conf.agile-france.org)
- [Appel à projets COVID-19](/appel-a-projets-covid-19)
- [frug'AgileFrance]

### 2019

- [Conférence Agile France](https://2019.conf.agile-france.org)
- [Agile Open France](http://agileopenfrance.com/)
- [Paris Test Conf](https://paristestconf.com)
- [Mobilizon](https://joinmobilizon.org) _(subvention)_

### 2018

- [Conférence Agile France](https://2018.conf.agile-france.org)
- [Agile Open France](http://agileopenfrance.com/)
- [Meetup OPEN Nouvelle-Calédonie](https://www.meetup.com/fr-FR/Meetup-des-professionnels-du-numerique-en-Nouvelle-Caledonie/events/252426773/)
- [Meetup Systémique et agilité](https://www.meetup.com/fr-FR/Systemique-Agilite-dialogue-pour-transformer-lentreprise/)

### 2017

- [Conférence Agile France](https://2017.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/810a24b6-2765-400b-aacc-da609cec39be-agile-open-france-2017-aof17.html)
- [Comparatif de post-its](https://medium.com/@MattiSG/stupid-science-i-compared-23-sticky-notes-to-help-you-spare-wallet-and-planet-fc9b97d88503)

### 2016

- [Conférence Agile France](https://2016.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/61f3f1b3-9ad7-4c40-b5ca-6316b134853f-agile-open-france-2016-aof16.html)
- [Geek Camp](https://www.meetup.com/fr-FR/software-craftsmanship-bdx/events/230739321)

### 2015

- [Conférence Agile France](https://2015.conf.agile-france.org)
- [Agile Open France](https://www.yuticket.com/association-agile-france/c4513d61-5d3b-4996-8fa2-2d76462a7c52-agile-open-france-2015-aof15.html)

### 2014

- [Conférence Agile France](https://2014.conf.agile-france.org)
- Agile Open France
- Geek Camp
- Agile Beirut
- Lean Camp


## Le mot de l’asso

Lors de la conférence AgileFrance a régulièrement eu lieu une prise de parole de l’association. Ces « mots » font partie de son histoire publique.

{% assign mots = site.mot_conference | reverse %}

{% for mot in mots -%}
- [{{ mot.title }}]({{ mot.url }})
{% endfor %}


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


## Documents

- [Statuts](/statuts)
- [Réglement intérieur](/reglement)
