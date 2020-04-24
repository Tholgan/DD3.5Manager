# Workflow git
1. [Rappel: Détail des différentes branches](#Détail-des-différentes-branches)

    1.1 [Branche master](#La-branche-principale-**`master`**)
    <br>1.2 [Branche develop](#La-branche-de-développement-**`develop`**)
    <br>1.2 [Les types de branches à partir de develop](#Les-types-de-branches-à-partir-de-**`develop`**)
2. [Rappel: Détail du workflow](#Détail-du-workflow)

Cher développeurs,

Afin de faciliter vos développements et de délivrer au mieux de votre travail nous avons mis en "gitflow" c'est à dire un ensemble de procédures à suivre lors que vous aurez à traiter une demande.

# Détail des différentes branches

![](https://miro.medium.com/max/823/1*uUpzVOpdFw5V-tJ_YvgFmA.png)

## La branche principale **`master`**
> contient le code source qui permettra de générer la release à deployer sur l'environnement de **production**.

## La branche de développement **`develop`**

> contient le code source qui permettra aux développeurs de traiter les différents types de demandes

## Les types de branches à partir de **`develop`**

`feature/*` Permet de répondre à la création d'une nouvelle fonctionnalité
`bugfix/*` Permet de corriger un bug de l'application


> _Note : Avant toute création de branche,  il vous faudra passer par la création d'un ticket dans l'outil d'azureDevOps._

# Détail du workflow

Lorsque vous serez amener à traiter une demande vous devrez suivre scrupuleusement les étapes suivantes:
1. Vous vous positionner sur la branche de développement
2. Créer votre branche à partir de la branche de développement en spécifiant sont type (feature/ bugfix)
3. (optionel peut être fait après) Vous poussez votre branche local sur le repository partagé
4. Vous effectuer votre développement en favorisant de petits commits
5. Vous poussez votre travail
6. Vous effectuer votre Pull Request via l'outil azur prévu à cet effet.




