# Prise en main du code

## Etape 1 :
Ajouter tout au path : appeler simu_addpath()

## Etape 2 : 
Vérifier que le code fonctionne correctement en lançant tous les tests unitaires du dossier *Unitests*. 

# Simulation et Simulation_Placement 
Ce sont deux fonctions qui appliquent le traitement multi-hypothèses avec la possibilité de définir le nombre de filtres Doppler. Elles ont besoin de connaître le scénario et la configuration du TS. Elles nécessitent aussi un pré-chargement des IQs.
***Simulation*** réalise un placement régulier des hypothèses selon leur nombre tandis que ***Simulation_Placement*** prend comme arguments des placements quelconques des hypothèses.


