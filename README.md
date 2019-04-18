# Python---Wine-quality
Cross-validation : GridSearchCV VS manuellement

Objectif : ré-implémenter la fonction de validation croisée de la libraire scikit-learn (la fonction GridSearchCV), 
dans l’objectif d’effectuer la classification du dataset sur la qualité du vin.

L’algorithme devra permettre d’optimiser l’accuracy du modèle. 
La fonction prendra en entrée le tableau des hyperparamètres à tester ainsi que le nombre de folds. 
On utilisera des folds exacts (non randomisé) afin de pouvoir comparer les résultats avec le GridSearchCV de scikit-learn.
