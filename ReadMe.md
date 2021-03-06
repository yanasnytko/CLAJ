<!-- omit in toc -->
# CLAJ (Site multipages)

- [Infos sur le client](#infos-sur-le-client)
  - [Buts du CLAJ](#buts-du-claj)
  - [Public cible](#public-cible)
  - [Buts du site](#buts-du-site)
  - [Infos de contact](#infos-de-contact)
- [Techniquement parlant](#techniquement-parlant)
- [Fichiers reçus](#fichiers-reçus)
  - [Polices](#polices)
  - [Couleurs](#couleurs)
- [Analyse du site](#analyse-du-site)
  - [Globalement](#globalement)
  - [Arborescence](#arborescence)
- [Questions](#questions)
  - [Prioritaires](#prioritaires)
  - [Globales](#globales)
  - [Contenu](#contenu)
  - [Recherches](#recherches)

:bulb: Voir l'[analyse fonctionnelle](AnalyseFonctionnelle.md) !

:bulb: Voir le [fichier SCRUM](SCRUM.md) !

:bulb: Voir les [backlogs](Backlogs.md) !

Ce projet est réalisé par :
|                | Joéllie                          | Mohamed   | Rachel                  | Yana                       |
| -------------- | -------------------------------- | --------- | ----------------------- | -------------------------- |
| **Tâches**     | Structure, contenu, UX et Design | Front-End | Front-End, SCRUM Master | Back-end - Project manager |
| **Complement** | support                          |           | design, support         | illus / design ?           |

## Infos sur le client

**CLAJ** : *Centre Liégeois d'Aide aux Jeunes* AMO, service d'Actions (avant : Aide) en Milieu Ouvert. Le centre a déjà un [site web](http://claj.be/), ainsi qu'une [page Facebook](https://www.facebook.com/centreliegeoisdaideauxjeunes/). Le contenu de l'ancien site est à reprendre, c'est récupéré.

:bulb: Le client rencontre un problème d'accès d'[OVH](https://www.ovh.com/fr/) (un cloud, hébergement Internet).

### Buts du CLAJ

Un soutien **socio-éducatif**, une aide préventive dans le milieu de vie (famille, école, quartier, ...) et les rapports avec l'environnement social, grâce aux :

- aides individuelles ;
- actions communautaires ;
- actions collectives ;
- actions de prévention.

### Public cible

- Actuel et potentiel ;
- Les **jeunes** ;
- 0 à 18-20 ans ;
- Les familles / proches des jeunes ;
- Autres intervenants auprès de jeunes (écoles, services sociaux, acteurs jeunesse, acteurs de la santé, ...) ;
- Partenaires.

:bulb: Il y a 6 antennes à Liège !

### Buts du site

- Regrouper des **informations** sur le CLAJ ;
- Informer sur les services, missions, activités, projets ;
- Servir de flux vers les pages extérieures ([Facebook](https://www.facebook.com/centreliegeoisdaideauxjeunes/)) ;
- Afficher les **evènements** crées sur [Facebook](https://www.facebook.com/centreliegeoisdaideauxjeunes/) ;
- **Contact** ;
- Visibilité du public et des partenaires (réseau) actuels et potentiels.

### Infos de contact

- **Personne de contact :** *Martin Snoeck*, éducateur ;
- **Mail :** claj.martinsnoeck@gmail.com ;
- **Téléphone :** 04 344 44 72.

**+** Catherine, claj.catherine@gmail.com.

## Techniquement parlant

- Conserver l’**arborescence**, mais à ré-évaluer et les **structures des pages** sont à retravailler ;

- **Responsive** - une version simplifiée pour smartphone ;

- **Sécuriser** le site (httpS) ;

- **Animations** flash  à jeter ou à mettre à jour ;
(éventuellement transformer les fichiers .swf en animation) ;

- Il faut que le client puisse **mettre à jour des contenus** ;

- Créer des **adresses mail** *@claj.be* avec le nom de domaine ;

- Intégrer un plugin **Google Maps** pour référencer les différents CLAJ de Liège (exit la map custom) ;

- **Plugin event** à intégrer (lien aux réseaux sociaux).

:bulb: Il faut respecter la **charte graphique** (cf. flyers et dépliants). Le **logo** existant est à garder (pas de changement possible).

## Fichiers reçus

- **Logo** (blanc/vert, sur fonds blanc/vert/rose avec et sans baseline) ;

![Logo](screens/logo.jpg)

- Fichier Photoshop avec le **fond** pour Header ;

![Fond](screens/fond.JPG)

- Affiche (ai, pdf) ;

![Affiche](screens/affiche.JPG)

- Dépliant (ai, pdf) ;

![depliant](screens/depliant1.JPG)
![depliant](screens/depliant2.JPG)

- En-tête et bas de page (ai, pdf) ;

![entete](screens/entete.JPG)
![entete](screens/basdepage.JPG)

- Flyer (ai, pdf) ;

![Flyer](screens/flyer.JPG)

- Plan / map (ai, pdf, jpg, tif) ;

![Map](screens/map.JPG)

- Dossier du site :
  - pages html,
  - css,
  - javascript,
  - dossiers de sécurité hts,
  - google analytics,
  - icons (gif),
  - images (jpg, png),
  - animations (gif, swf),
  - docs pour jeunes (dossier *img* - jpg, pdf, gif).

### Polices

- Myriad Roman ;

![Myriand Roman](screens/polices/myriad-roman.png)

- Myriad Bold ;

![Myriand Bold](screens/polices/myriad-bold.png)

- Kristen ITC Regilar ;

![Kristen ITC Regilar](screens/polices/kristen.jpg)

- Century Gothic Bold ;

![Century Gothic Bold](screens/polices/century-gothic-bold.png)

- Maiandra GD Regular ;

![Maiandra GD Regular](screens/polices/maiandra.png)

- Antiqua Book.

![Antiqua Book](screens/polices/antiqua-book.png)

### Couleurs

:bulb: Les noms en italique sont ceux de logo.

- ![Jaune](screens/colors/j.JPG) **Jaune**, #FAE920, rgb(250, 233, 32) ;

- ![Jaune-orange](screens/colors/j-o.JPG) **Jaune-orange**, #F5C509, rgb(245, 197, 9) ;

- ![Vert](screens/colors/v.JPG) **Vert**, #2D692D, rgb(45, 105, 45) ;

- Dégradé de ![Vert-blue](screens/colors/v-b.JPG) **Vert-blue**, #279037, rgb(39, 144, 55) vers ![Vert-jaune](screens/colors/v-j.JPG) **Vert-jaune**, #9CC429, rgb(156, 196, 41) ;
![Dégradé](screens/colors/degrade.JPG)

- ![Vert-jaune du logo](screens/colors/v-j-logo.JPG) *Vert-jaune*, #4B9228, rgb(75, 146, 40) ;

- ![Blanc-blue](screens/colors/b-b.JPG) **Blanc-blue**, #CAE8F3, rgb(202, 232, 243) ;

- ![Blue](screens/colors/b.JPG) **Blue**, #2084C6, rgb(32, 132, 198) ;

- ![Rose](screens/colors/rose.JPG) **Rose**, #EA5599, rgb(234, 85, 153) ;

- ![Mauve](screens/colors/m.JPG) *Mauve*, #C82280, rgb(200, 34, 128) ;

- ![Rouge](screens/colors/rouge.JPG) **Rouge**, #E34522, rgb(227, 69, 34).

## Analyse du site

### Globalement

- Header = Logo + baseline et illustration avec un fond incorporé (cf. fichier Photoshop) ;

![Header](screens/header.JPG)

- Fond en dégradé, de vert-jaune à vert-blue ;
- Animations dessinées très lentes ;
- Illustrations ;
- Logos des partenaires.

:bulb: Pas des liens claires vers les Facebook !

### Arborescence

![L'arborescense](screens/nav.JPG)

1. *Qui sommes-nous ?* (Description, adresse)

2. *Pour qui, pour quoi ?*
   1. Qui : 5 boutons qui déclanchent des pop-ups ;
   ![Pour qui avec pop-up](screens/qui.JPG)
   2. Quoi : 28 paragraphes qui s'agrandissent au survole.
   ![Pour quoi](screens/quoi.JPG)

3. *Le CLAJ près de chez toi !* (Carte interactive)

4. *Quoi d'neuf ?*
   1. Agenda - renvoie vers une page des évènements ;
   2. Outils pédagogiques - renvoie vers une page avec des pdf et leur déscription.

5. *Nos amis...* (Partenaires)

6. *Nous contacter* (Toutes les adresses avec jolies illus)

## Questions

### Prioritaires

- **Historique** et identité de l’entreprise (valeurs, philosophie, identité,…) ?

- Identifier le **problème** à résoudre (visibilité, clarté, notoriété, revenu, budget,…) ;

- Définir des **actions prioritaires** ;

- Existe-t-il une **charte graphique** (nom des polices, couleurs, taille, etc) ? Non

- Quelles sont les **valeurs** et objectifs ?

- Quelle serait la solution idéale s’il n’y avait pas de contrainte de temps et de budget ?

- Qu’est-ce que le site devrait absolument contenir ?

### Globales

- Toujours spécifier "**AMO**" ? Oui

- Est-ce que le client a toujours ses accès à [**OVH**](https://www.ovh.com/fr/) ? Non

- Une ou 7 pages **Facebook** ? Une

- Un des buts est "regrouper infos sur le CLAJ" : infos institutionnelles ou blog ?

- Quand le client parle de mettre à jour le contenu, jusqu'où veut-il aller ? Supprimer des blocs, changer des titres, adresses ?

- Clarifier **plugin** Facebook et events ;

- Faire lien avec page **Instagram** ? Non

- Les mêmes activités dans toutes les **antennes** ? Quelles sont les spécificités par antenne ? Quels sont les services précis ?

- Comment se font les **interactions** avec l'utilisateur (téléphone, mail, site web, réseaux sociaux, en présentiel, …) ?

- Que disent les utilisateurs sur le site ? Dépassé

- Comment le client mesure-t-il le succès de son projet (augmentation client, augmentation des inscriptions, changement d’image, …) ?

- Avez-vous souvent des demandes dans d'autres langues que le français ?

### Contenu

- Google **Maps** est payant - ok pour un équivalent ?

- Faut-il un **calendrier** ?

- Faut-il une **newsletter** ?

- De quelle manière veulent-ils voir apparaître les **partenaires** ?

- Quid logos *CAAJ* et *Communauté française* dans l'intro ?

- Peut-on enlever le fond photo vert du banner ?

- Mettre le banner en footer ? Voire carrément supprimer (exemple UCM) car cela n'altère pas leur identité ;

- Ok pour retranscrire PDF en contenu texte (référencement) ?

### Recherches

- [ ] FB developper doc - comment récuperer les events et les publications dans l'API ;
- [ ] Regarder (à l'internationale) les sites des autres centres des jeunes.

:bulb: Voir l'[analyse fonctionnelle](AnalyseFonctionnelle.md) !

:bulb: Voir le [fichier SCRUM](SCRUM.md) !

:bulb: Voir les [backlogs](Backlogs.md) !
