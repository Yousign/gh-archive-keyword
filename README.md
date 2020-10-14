# Challenge GH Archive Keyword

>  tl;dr :  l'objectif de ce challenge est de développer avec [GH Archive](https://www.gharchive.org/) 
>  une API REST en PHP sur la présence d'un mot-clé parmi les messages de commits d'un jour donné, 
>  par exemple une courbe du nombre de commits dans la journée du 14/02/2018 qui ont le mot-clé "love".

## Évaluation :trophy: 

Le code sera évalué sur les critères suivants *(laissés à votre libre interprétation)* :

* Respect des consignes
* Rigueur
* Qualité du code
* Qualité des features délivrées
* Documentation

## Consignes :woman_teacher:

* Vous livrerez votre projet sur un dépôt GitHub (public ou privé, à votre convenance)
* Vous réaliserez l'ensemble du scope fonctionnel spécifié ci-dessous
* Vous rendrez le livrable **dans un délai de 7 jours**
* Vous utiliserez **Symfony 4.4** et **PHP 7.4**
* Vous utiliserez un SGBD relationnel : **PostgreSQL, MySQL ou MariaDB**
* Vous devrez **exploiter les fichiers `.json.gz`** disponible sur [GH Archive](https://www.gharchive.org/) ; en d'autres termes vous n'utiliserez **pas** le dataset public Google BigQuery pour l'import des données
* Vous n'utiliserez **pas** de framework d'API comme FOSRestBundle ou API Platform

## Objectifs :rocket:

[GH Archive](https://www.gharchive.org/) est un site qui permet de retrouver l'historique 
des évènements publiques qui ont été réalisés sur GitHub pendant une période donnée.

L'objectif premier de ce challenge est de récupérer certains [événements](https://docs.github.com/en/developers/webhooks-and-events/github-event-types)
de [GH Archive](https://www.gharchive.org/) afin de les stocker dans une base de données. 
Cette partie sera réalisée par une commande CLI.

Il s'agira ensuite de créer une API REST avec 1 ou plusieurs routes permettant d'aller interroger les informations 
de cette base de données, en renseignant une **date** et **un mot-clé**.

Cette API doit notamment permettre de répondre aux besoins de l'interface suivante : 

![Capture d'écran du résultat attendu dans l'interface web](./challenge-gh-keyword.png)

**Nous vous encourageons à vous faire plaisir pendant ce challenge !**

# Bon courage ! :muscle:
