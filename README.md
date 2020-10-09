# Challenge GH Archive Keyword

>  tl;dr :  l'objectif de ce challenge est de développer avec [GH Archive](https://www.gharchive.org/) 
>  une API REST en PHP sur la présence d'un mot-clé parmi les messages de commits d'un jour donné, 
>  par exemple une courbe du nombre de commits dans la journée du 14/02/2018 qui ont le mot-clé "love".

## Temps de réalisation :alarm_clock:

Ce challenge a été pensé pour être réalisé dans **un délai court**, c'est à vous d'y accorder 
le temps que vous jugez nécessaire.

Vous pouvez passer plus de temps pour le compléter de manière facultative. Il n'est pas nécessaire 
de terminer complètement le challenge pour envoyer votre participation, l'essentiel est d'avoir 
assez de matière pour en discuter ensuite.

## Évaluation :trophy: 

Le code sera évalué sur les critères suivants *(laissés à votre libre interprétation)* :

* Respect des consignes
* Rigueur
* Qualité du code
* Qualité des features délivrées
* Documentation

On priorisera avant tout la qualité des features délivrées à la quantité : on préférera 
voir une seule feature de très bonne qualité à une dizaine de features faites à la va-vite.

## Consignes :woman_teacher:

* Vous livrerez votre projet sur un dépôt GitHub (public ou privé, à votre convenance).
* Vous rendrez le livrable **dans un délai de 7 jours**.
* Vous utiliserez Symfony 4.4 et PHP 7.4.
* Vous utiliserez un SGBD relationnel : PostgreSQL, MySQL ou MariaDB.

## Objectifs :rocket:

[GH Archive](https://www.gharchive.org/) est un site qui permet de retrouver l'historique 
des évènements publiques qui ont été réalisés sur GitHub pendant une période donnée.

L'objectif premier de ce challenge est de récupérer certains [événements](https://docs.github.com/en/developers/webhooks-and-events/github-event-types)
de [GH Archive](https://www.gharchive.org/) afin de les stocker dans une base de données. 
Cette partie sera réalisée par un script lancé en ligne de commandes.

Il s'agira ensuite de créer une API REST avec 1 ou plusieurs routes permettant d'aller interroger les informations 
de cette base de données, en renseignant une **date** et **un mot-clé**.

Cette API doit permettre de répondre aux besoins de l'interface suivante : 

![Capture d'écran du résultat attendu dans l'interface web](./challenge-gh-keyword.png)

**Nous vous encourageons à vous faire plaisir pendant ce challenge !**

# Bon courage ! :muscle:
