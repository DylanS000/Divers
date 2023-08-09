# Prise en main du code

## Etape 1 :
Ajouter tout au path : appeler simu_addpath()

## Etape 2 : 
Lancer le script ***TestUnitaireIDONE*** et vérifier qu'il fonctionne correctement. L'exécution est courte.

# Simulation et Simulation_Placement 
Ce sont deux fonctions qui appliquent le traitement multi-hypothèses avec la possibilité de définir le nombre de filtres Doppler. Elles ont besoin de connaître le scénario et la configuration du TS. Elles nécessitent aussi un pré-chargement des IQs.
***Simulation*** réalise un placement régulier des hypothèses selon leur nombre tandis que ***Simulation_Placement*** prend comme arguments des placements quelconques des hypothèses.


# De l'exercitation 

Si l'utilisateur désire faire ou refaire un paramétrage des algorithmes,  il lui suffit de s'intéresser aux routines qui se trouvent dans le dossier *ParametrageDesAlgorithmes*.

Dans le script ***TestsSimulation*** se trouve les analyses de l'influence de la modification du nombre de filtres Doppler. Son exécution prend 3 à 4 heures.

Le script ***ParametrageIDONE*** permet à l'utilisateur de lancer une comparaison de différents paramétrages du IDONE. En fin de script, il y a des indications sur les paramètres de l'algorithme à choisir. 


# Pour finir


Le dossier *Optimisation* contient tous les codes des fonctions réalisant une optimisation du nombre d'hypothèses et/ou de leur placement. 

Le dossier *Res* contient de nombreux résultats de simulations : comparaisons d'algorithmes, paramétrages, etc.

Enfin les dossiers *bibliotheque*,*Scenarios* et *RESULTATS* sont inhérents au TS. 

