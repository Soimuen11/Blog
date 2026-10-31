---
layout: post
title: "Le FreeWiki : un wiki IT libre et gratuit pour tous !"
published: true
category: IT
tags: [linux, windows, powershell, bash, troubleshooting, ffmpeg]
author: Philippe Iannetta
---

Bonjour à tous ! 🙂

Aujourd'hui, j'aimerais vous parler d'un projet qui me tient particulièrement à
cœur : le **FreeWiki**.

Ceux qui me connaissent un peu savent à quel point j'aime écrire. Quant à ceux
qui ont eu le privilège (si, si, j'insiste 🤣) de me supporter au boulot, que
ce soit chez [Econocom](https://econocom.com), [Spie ICS](https://spie.com) ou
ailleurs, ils savent aussi à quel point j'aime documenter.

Vous l'aurez compris : nous allons parler documentation, informatique et
partage de connaissances !

Un projet qui pourrait bien devenir le vôtre, si vous acceptez cette mission.

J'ai nommé le [FreeWiki](https://freewiki.phiannetta.xyz) !

## L'histoire du FreeWiki

Né officiellement le 4 juin 2020, le
[FreeWiki](https://freewiki.phiannetta.xyz) avait, à l'origine, pour vocation
de documenter mon expérience de Linux en tant que système d'exploitation de
bureau.

À l'époque, je ne m'imaginais pas encore devenir sysadmin. Je cherchais
simplement à apporter ma pierre à l'édifice en tant que *power user*. Mon
objectif était assez simple : centraliser mes problèmes, les solutions que je
trouvais et les astuces que je découvrais, afin de pouvoir les retrouver
facilement, où que je sois.

C'était quelques années avant que j'adopte [Joplin](https://joplinapp.org/),
mais ça, ce sera le sujet d'un autre article !

Le FreeWiki a également été ma première expérience avec la combinaison
[Jekyll](https://jekyllrb.com/) + [GitHub
Pages](https://docs.github.com/en/pages). Je connaissais déjà bien GitHub pour
y avoir hébergé plusieurs projets, mais Jekyll était une découverte totale.

Vous vous en doutez : l'expérience m'a plu, puisque j'ai renouvelé l'aventure
avec mon [blog](https://blog.phiannetta.xyz).

Puis, au fil du temps, le wiki a été quelque peu délaissé. Je savais pourtant
qu'il faudrait m'y replonger un jour.

Ce jour est finalement arrivé en août 2026.

Un ami italien, Luca, de [semplicemente.io](https://semplicemente.io), m'a
proposé une refonte du design. Cette proposition a été le déclic dont j'avais
besoin pour remettre le projet sur les rails.

Mais plutôt que de simplement lui donner un coup de peinture, pourquoi ne pas
repenser aussi son contenu et son utilité ?

C'est là que vous entrez en jeu.

## Pourquoi un wiki IT libre ?

Quand on change d'entreprise, on ne sait jamais vraiment quelle documentation
nous attend. Parfois, tout est parfaitement organisé. Parfois, les procédures
sont dispersées entre différents outils, les informations sont incomplètes et
certaines solutions ne survivent qu'au fond d'un ticket ou dans les souvenirs
d'un collègue.

Et parfois, il faut tout redécouvrir.

Le FreeWiki pourrait contribuer à résoudre une partie de ce problème.

L'idée est de constituer une base de connaissances techniques accessible à
tous, dans laquelle chacun pourrait retrouver des commandes, des procédures,
des astuces et des solutions à des problèmes courants.

Bien entendu, **le FreeWiki n'a pas vocation à héberger des informations
confidentielles**. Il ne s'agit pas de publier la documentation interne de son
entreprise, ni de divulguer des informations propres à une infrastructure.

En revanche, rien n'empêche de **partager une solution générique à un problème rencontré au travail**,
à condition d'anonymiser et de généraliser les
informations pertinentes : noms de machines, adresses, variables, chemins
sensibles et autres éléments propres à l'environnement concerné.

L'objectif n'est pas de documenter une infrastructure particulière, mais de
transmettre une méthode qui pourra être utile à d'autres.

Après tout, si vous avez déjà passé une heure à résoudre un problème avant de
trouver la solution sur un forum ou dans un vieux billet de blog, vous savez à
quel point une documentation bien faite peut nous faire gagner du temps.

Et si nous pouvions, à notre tour, éviter cette heure de recherche à quelqu'un
d'autre ?

## Deux univers, une même envie de partager

Historiquement orienté vers Linux sur desktop, le FreeWiki conservera cette
dimension. Mais j'aimerais désormais lui donner une portée plus large, en
intégrant davantage de contenu destiné aux professionnels de l'informatique.

Voici la structure que j'envisage actuellement.

### Power User : l'informatique au quotidien

Cette partie restera consacrée à l'utilisation personnelle de l'informatique,
au desktop et au homelab.

On pourrait notamment y retrouver :

- **FFmpeg** : commandes et exemples pour manipuler des fichiers audio et
  vidéo.
- **Scripts** : petits outils et automatisations utiles au quotidien.
- **Troubleshooting** : problèmes rencontrés, diagnostics et solutions.
- **Tips & Tricks** : astuces et bonnes pratiques.
- **Resources** : liens et ressources utiles.

C'est l'ADN historique du FreeWiki, et je tiens à le conserver.

### Sysadmin : des ressources pour les professionnels

Cette seconde partie sera davantage tournée vers l'administration système et
les environnements professionnels.

L'idée est de proposer, entre autres :

- **Linux** : Bash, ligne de commande et bonnes pratiques.
- **Windows** : PowerShell, administration et bonnes pratiques.
- **Cheatsheets** : des fiches de référence rapides, notamment pour retrouver
  des commandes et comparer les usages entre systèmes.
- **Procedures** : des procédures génériques, par exemple pour nettoyer `/var`,
  configurer un point de montage dédié, construire une VM de façon standardisée
  ou effectuer certaines opérations de maintenance. Bref, toutes les procédures
  qui pourraient concerner un contrôle de supervision ou autre action
  généralisable, qu'elle relève du RUN ou du BUILD.
- **Resources** : de la documentation et des liens utiles aux administrateurs
  système.

Cette organisation est encore en réflexion. Elle évoluera en fonction des
besoins, des contenus disponibles et, je l'espère, de vos contributions.

## Et si nous construisions le FreeWiki ensemble ?

Je ne veux pas que le FreeWiki soit simplement un site sur lequel je publie mes
propres notes. J'aimerais qu'il devienne une ressource utile à davantage de
monde.

Vous êtes sysadmin, technicien, développeur ou simplement passionné
d'informatique ? Vous avez des astuces, des procédures génériques ou des
solutions à des problèmes récurrents que vous aimeriez partager ?

Alors, vous êtes les bienvenus !

Une documentation n'a pas besoin d'être révolutionnaire pour être utile. Une
commande bien expliquée, une procédure claire ou un dépannage correctement
documenté peuvent faire gagner un temps précieux à quelqu'un d'autre.

Je ne sais pas encore combien de temps je pourrai consacrer au projet au cours
des prochains mois. C'est justement l'une des raisons pour lesquelles
j'aimerais voir davantage de personnes s'impliquer :

**un projet collectif a plus de chances de durer qu'un wiki reposant sur une seule personne.**

Vous pouvez dès maintenant découvrir le
[FreeWiki](https://freewiki.phiannetta.xyz) et consulter son dépôt sur GitHub en cliquant [ici](https://github.com/Soimuen11/FreeWiki).

N'hésitez pas à le partager avec vos collègues, vos amis et tous ceux qui
pourraient y trouver leur bonheur.

Et si vous souhaitez contribuer, toute aide sera appréciée !

J'ajoute que vous pouvez participer tant au développement du site qu'à celui
des procédures, et ceux peu importe la langue. Pour l'instant, la seule langue
disponible est l'anglais. Mais rien n'empêche d'étudier l'ajout d'autres
langues plus tard !

À plusieurs, nous serons plus forts. Et surtout, nous éviterons peut-être à
quelques collègues de passer leur vendredi après-midi à chercher pourquoi leur
script ne fonctionne pas (ou de gaspiller des tokens sur Claude pour un
problème dont vous connaissez déjà la solution). 😉

À bientôt sur le FreeWiki !
