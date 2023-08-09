# Prise en main du code

## Etape 1 :
Ajouter tout au path : appeler simu_addpath()

## Etape 2 : 
Faire les tests unitaires du dossier TestsUnitaires et vérifier que tout fonctionne correctement.

# Simulation et Simulation_Placement 
Ce sont deux fonctions qui appliquent le traitement multi-hypothèses. Elles ont besoin de connaître le scénario et la configuration du TS. Elles nécessitent aussi un pré-chargement des IQs.
***Simulation*** réalise un placement régulier des hypothèses selon leur nombre tandis que ***Simulation_Placement*** prend comme arguments des placements quelconques des hypothèses.


# De l'exercitation 

Si l'utilisateur désire faire ou refaire un paramétrage des algorithmes,  il lui suffit de s'intéresser aux routines qui se trouvent dans le dossier *ParametrageDesAlgorithmes*.

Dans le script ***TestsOptimisation*** se trouve des lancers des heuristiques et de la combinaison heuristique de descente/algorithme de placement. Pour choisir quel algorithme lancer, il suffit de se référer aux lignes 16 à 21 du script. Ce script peut être vu à la fois comme des tests unitaires et comme des exemples d'utilisation des différents algorithmes. 

Le script ***ComparaisonAlgosDePlacement*** permet de comparer tous les algorithmes de placement dans la meilleure configuration de leur paramétrage et sur une même simulation 
avec plus d'IQs. Des suggestions sur les valeurs que peuvent prendre les différents paramètres et/ou les valeurs par défaut à choisir, sont également faites dans ce script.
Pour choisir quel(s) algorithme(s) exécuter, il suffit de se rendre aux lignes 85-88.  






# Pour finir


Le dossier *Optimisation* contient tous les codes des fonctions réalisant une optimisation du nombre d'hypothèses et/ou de leur placement. 

Le dossier *Res* contient de nombreux résultats de simulations : comparaisons d'algorithmes, paramétrages, etc.

Enfin les dossiers *bibliotheque*,*Scenarios* et *RESULTATS* sont inhérents au TS. 

