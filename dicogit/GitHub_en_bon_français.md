# Github en bon français
 
Ce petit glossaire a pour but d'expliciter dans un langage courant les différents vocabulaires issus de l'anglais, inhérents à l'utilisation de Git et de GitHub. 
 
## Git

Logiciel libre permettant de versionner des projets de manière distribuée. Chaque contributeur peut travailler sur une copie du dépôt à distance sur son ordinateur. L'utilisation de Git va permettre d'obtenir une frise chronologique de son projet et ainsi faciliter la consultation de l'historique des modifications. Grâce à sa gestion de graphe très puissante, Git permet de revenir facilement à un état antérieur du projet par exemple, de comparer les modifications entre deux états, etc. Il est aujourd'hui le logiciel de versionnement le plus populaire au monde et bénéficie d'un écosystème important.

## GitHub, GitLab, BitBucket

Services en ligne servant de dépôt central pour des dépôts Git, proposant une interface graphique pour faciliter la collaboration à distance. Ces services permettent d'effectuer une partie des opérations en ligne sans avoir à passer par la ligne de commande : modification de fichier via un éditeur, enregistrement des modifications, création de branche, demande de fusion, de publication de version, Wiki, Kanban Projet, etc.

* [GitHub](https://github.com/)
* [GitLab](https://about.gitlab.com/)
* [BitBucket](https://bitbucket.org/)

## GitHub Desktop

Application de bureau, qui permet de visualiser le graphe, l'historique et la gestion de certaines opérations sur ses projets versionnés (clone, branch, commit, pull, push, diff, etc.)

[https://desktop.github.com/](https://desktop.github.com/) disponible pour Mac et Windows.

## GitKraken

Application de bureau multi-plate-forme (Mac, Windows, Linux) proposant une interface graphique pour la gestion des dépôts.

Site : [https://www.gitkraken.com](https://www.gitkraken.com)

## Dépôt

Ensemble des fichiers d'un projet versionné avec Git, correspond à un dossier de travail sur sa machine.

## Cloner

Recopier un dépôt Git distant sur son ordinateur afin de pouvoir effectuer des modifications dessus.

## Commit

Sauvegarde horodatée avec un titre et une description (optionnelle) qui permet de préciser l'intention du changement apporté par la modification. Une bonne pratique consiste à livrer des ensembles de modifications qui font sens,  car idéalement on devrait pouvoir supprimer cet enregistrement de modification. Plus les commits sont unitaires, restreints, "atomiques" plus il est facile de suivre les modifications dans l'historique, les annuler ou les supprimer. Sur le graphe, un commit est représenté par un point.

## Stash

Commande Git qui permet de "Mettre de coté" des modifications en cours sans les enregistrer dans le graphe. C'est un brouillon, un ensemble de modifications pas terminées.

## Fork

Bifurcation. *Forker* désigne le fait de recopier un dépôt Git, dans l'optique de pouvoir y faire des modifications. Cette opération est nécéssaire quand il faut contribuer sur un dépôt Git sur lequel on ne possède pas les droits de publication ou de fusion. Un *fork* désigne par extension également un logiciel créé à partir du code source d'un autre.

## Branch

Branche de travail. Une branche permet de faire des modifications qui parallèlement à la branche principale. C'est une bonne pratique et une manière d'organiser les modifications. 

On essaie de garder la branche *master* (le tronc) le plus "propre" possible (stable, utilisable, de qualité), on expérimente à coté et quand on est prêt on peut alors incorporer dans le tronc (la branche principale). Faire des branches courtes est le meilleur moyen d'ajouter régulièrement de la valeur pour les utilisateurs et de faciliter les opérations de fusion avec la branche maître. Les branches donnent du relief au développement.

Le début d'une branche c'est simplement la référence du *commit* à partir duquel la bifurcation a été faite. Une branche ne coûte rien à faire et c'est une des principales forces de Git. Abusez-en !

## Pull

Récupérer les modifications du dépôt distant dans le dépôt local.

## Push

Pousser les modifications d'un dépôt local vers un dépôt distant. 

## Remote

Nom d'un dépôt distant. Souvent `origin` par défaut. Comme il est possible de travailler avec plusieurs dépôts distants, on donne un nom à chaque dépôt. Il est ainsi possible de récupérer les modifications de n'importe quel dépôt. 

## Issue

Fil de discussion sur GitHub, qui permet de remonter des anomalies, proposer des fonctionnalités ou poser des questions.
Comme les Post-it™ d'un bac à sable, c'est le point de départ des discussions sur les choses à faire.

## Pull request

Proposition de modification par quelqu'un qui n'est pas accrédité sur un dépôt (dossier). Procédure : récupérer le dépôt, modifier la copie locale et soumettre la modification. Permet de procéder à une revue (humaine ou automatisée).

Il est possible de créer une branche et de soumettre une *pull request* sur GitHub afin de pouvoir engager des discussions sur les choses à faire.

## Review

Revue, relecture. Lorsqu'un contributeur soumet une modification, elle est ensuite passée en revue avant d'être acceptée. GitHub intègre une gestion des revues, qui permet de faire des commentaires, d'approuver ou de désapprouver une demande. Certains processus de publication imposent les revues par une ou deux personnes distinctes, car plusieurs avis valent mieux qu'un.

Les revues ont beaucoup de vertus, elles permettent d'améliorer la qualité, facilitent l'appropriation collective et le partage des responsabilités dans l'équipe.

## Rebase

Regroupement et fusion des version de sauvegarde (*commit*) d'une branche pour limiter le nombre de sauvegardes visibles ensuite dans la branche principale.

## Fix

Réparation, correction d'une anomalie.

## Release

Version numérotée - [sémantiquement](http://semver.org/lang/fr/) de préférence - correspondant à une étape notable du projet (ajout de nouvelle fonctionnalité, corrections, etc.) accompagné d'une historique des modifications depuis la version précédente.
Exemple:  Publication de la version 1.2 de la documentation, publication de la version 0.12.1 du logiciel.
Sur GitHub, les releases peuvent être créer facilement à partir de tags définis.

## Merge

Action de fusionner deux branches.

## Label

Possibilité de tagger des issues ou des pull-requests sur GitHub pour organiser les demandes. 

## GitHub Pages 

Service gratuit proposé par GitHub qui permet d'héberger le code source d'un site web statique dans un dépôt, de l'héberger et de le servir.
Beaucoup de sites de logiciels, de documentation sont ainsi hébergés sur GitHub.

Site: [https://pages.github.com/](https://pages.github.com/)

## GitLab Pages

Service similaire à GitHub Pages proposé par GitLab. 

Site : [https://pages.gitlab.io/](https://pages.gitlab.io/)

## Jekyll

Générateur de site statique supporté par défaut par GitHub Pages. Jekyll permet de structure ses contenus dans des formats textes comme YAML, JSON, CSV, Markdown.

Site officiel : [http://jekyllrb.com/](http://jekyllrb.com/)

## Liquid

Langage de templating, développé à l'origine la création de thèmes pour le service Shopify et utilisé par Jekyll, qui permet d'insérer un peu d'intelligence dans les modèles (conditions, boucles, etc.).

Documentation hébergé sur GitHub Pages : [http://shopify.github.io/liquid/](http://shopify.github.io/liquid/)
