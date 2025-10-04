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
- [Pierre Grigoletto](https://www.linkedin.com/in/pierre-grigoletto/)  - démissionnaire au 28/09/2025 - 
- [Natacha Fourmy](https://www.linkedin.com/in/natacha-fourmy/)

Les bureaux successifs ont donné des orientations à l’association qui ont construit son histoire.

{% assign bureaux = site.bureau | reverse %}

{% for bureau in bureaux -%}
- {{ bureau.election | date: "%Y" }} — [{{ bureau.title }}]({{ bureau.url }})
{% endfor %}

Rôle et responsabilité du bureau

-	Principes de base

Le bureau de l’association a essentiellement un rôle administratif.
Il n'a pas pour vocation d’animer l’association. Ce rôle est celui de tous les adhérents. 
-	Les initiatives de l’association
	
Chaque adhérent de l’association est libre de lancer et piloter une initiative dans le respect des statuts et du règlement intérieur de l’association. Tous les adhérents de l’association peuvent demander à y participer.
Le bureau ne lance ni ne pilote pas les initiatives (validation, animation, etc.) même si un de ses membres peut le faire en tant qu’adhérent de l’association. Le bureau peut apporter son aide aux adhérents qui souhaiteraient lancer une initiative et qui lui en ferait la demande.
-	Les outils (forum de discussion, site internet, droits d’accès des adhérents, communication, archives documentaires, comptabilité, etc.)

Le bureau est responsable des outils utilisés par l’association.
Il en a les droits administrateurs et est le seul habilité à y faire les évolutions ou interventions nécessaires (Exemples : évolution du site internet, ajout de droits d’accès à un nouvel adhérent, communication au nom de l’association, etc.).
Il peut déléguer à un adhérent de l’association des actions à faire sur ces outils, mais il en garde la responsabilité et la supervision.
-	Les initiatives extérieures soutenues par l’association (conférences)

Le bureau est responsable et pilote les échanges avec les organisateurs des initiatives extérieures soutenues par l’association (conférences).
Il peut déléguer à un adhérent de l’association des actions à faire avec ces organisateurs, mais il en garde la responsabilité et la supervision.

## États généraux

Le bureau a organisé en janvier 2022 des « [États généraux](/etats-generaux-2022) », une série d'ateliers pour penser ensemble le futur d'Agile France.

## Le mot de l’asso

Lors de la conférence AgileFrance a régulièrement eu lieu une prise de parole de l’association. Ces « mots » font partie de son histoire publique.

{% assign mots = site.mot_conference | reverse %}

{% for mot in mots -%}
- [{{ mot.title }}]({{ mot.url }})
{% endfor %}
