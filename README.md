# Projet AGL - Sujet BIGDATA
 Ce dépôt GitHub contient une conception détaillée pour une application interactive pour simplifier l'apprentissage de la Big Data. Elle proposera des modules d'apprentissage avec des scénarios simples, des animations et des illustrations pour rendre les concepts complexes plus accessibles. Notre motivation principale est de combler le manque d'outils interactifs pour les débutants dans le domaine de la Big Data, une compétence essentielle dans le paysage technologique actuel.

 ____________________________________________________________________________________________________

 ## Fonctionnalités :
 ### 1 - Modules d'apprentissage 



 ### 2 - Animations Pédagogiques 



 ### 3 - Quizz et Evaluations  



 ### 4 - Progression Personnalisér 



 ### 5 - Forum de Discussion  



 



 ____________________________________________________________________________________________________
## Structure du dépôt :
### Documents de conception : 
Comprend des documents détaillant l'architecture logicielle, les diagrammes de flux, les maquettes d'interface utilisateur, etc.

### Ressources supplémentaires :
Toute autre documentation ou ressource pertinente pour le développement et la conception de l'application.

 ____________________________________________________________________________________________________

## Contributions :
Les contributions et les commentaires sont les bienvenus ! Si vous avez des idées pour améliorer cette conception ou si vous souhaitez contribuer au développement de l'application, n'hésitez pas à soumettre des pull requests ou à ouvrir des issues.

 ____________________________________________________________________________________________________
## Conception :

![usecase](https://github.com/MolkaJebali/Projet-AGL---BIGDATA/assets/162985207/ddb6a8db-b72e-4637-b021-89e8573e79fd)



 ____________________________________________________________________________________________________
## Table de décision des tests de validation  :
### S'inscrire/Se connecter:
| Fonctionnalités                                                     | Test 1 | Test 2 | Test 3 | Test 4 |
|----------------------------------------------------------------------|--------|--------|--------|--------|
|  L'utilisateur n'est pas connecté ou inscrit |   F    |   T    |   T    |   T    |
| L'utilisateur accède à la fonctionnalité "S'inscrire/Se connecter"                   |       |   F    |   T    |    T    |
| L'utilisateur remplit le formulaire de connexion ou d'inscription.                 |       |       |   F     |  T      |
| L'utilisateur est inscrit avec un nouveau compte ou connecté avec un compte existant  |   F    |   F    |   F    |   T    |
|Nombre de jeux de tests | 2 | 2*n | 1 | 1 |

### Parcourir les Modules :

| Fonctionnalités                                                     | Test 1 | Test 2 | Test 3 | Test 4 |
|----------------------------------------------------------------------|--------|--------|--------|--------|
|  L'utilisateur est connecté |   F    |   T    |   T    |   T    |
| L'utilisateur accède à la fonctionnalité "Parcourir les Modules"                   |       |   F    |   T    |    T    |
| L'application charge la liste des modules disponibles et l'utilisateur visualise la liste des modules disponibles.                 |       |       |   F     |  T      |
| L'utilisateur peut choisir de sélectionner un module pour en savoir plus ou passer à une autre action dans l'application.  |   F    |   F    |   F    |   T    |
|Nombre de jeux de tests | 2 | 2*n | 1 | 1 |

### Compléter un Module :

| Fonctionnalités                                                     | Test 1 | Test 2 | Test 3 | Test 4 |
|----------------------------------------------------------------------|--------|--------|--------|--------|
|  L'utilisateur est connecté |   F    |   T    |   T    |   T    |
| L'utilisateur accède à la fonctionnalité "Compléter un Module"                   |       |   F    |   T    |    T    |
| L'application charge la liste des modules disponibles l'utilisateur sélectionne un module à compléter parmi la liste des modules disponibles.                 |       |       |   F     |  T      |
| L'utilisateur a accès au contenu complet du module choisi.   |   F    |   F    |   F    |   T    |
|Nombre de jeux de tests | 2 | 2*n | 1 | 1 |
