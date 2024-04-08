# Programme de Calcul du PGCD

Ce programme permet de calculer le Plus Grand Commun Diviseur (PGCD) de deux nombres entiers en utilisant l'algorithme d'Euclide.

## Déclaration des Variables

- `numA` et `numB` sont les nombres pour lesquels nous voulons trouver le PGCD.
- `temp` est une variable temporaire utilisée pour stocker une valeur pendant l'échange de `numA` et `numB`.

Type des variables `numA`, `numB`, `temp` : nombre

## Algorithme

### DÉBUT

1. **Demande à l'utilisateur d'entrer le premier nombre.**
   - ÉCRIRE "Saisissez le premier nombre entier"
   - LIRE `numA`
   
2. **Demande à l'utilisateur d'entrer le deuxième nombre.**
   - ÉCRIRE "Saisissez le second nombre entier"
   - LIRE `numB`

3. **La boucle continue tant que `numB` est différent de zéro.**
   - TANT QUE `numB` ≠ 0
     - Stocke la valeur actuelle de `numB` dans `temp`.
       - `temp` ← `numB`
       
     - Met à jour `numB` avec le reste de la division de `numA` par `numB`.
       - `numB` ← `numA` % `numB`
       
     - Met à jour `numA` avec la valeur précédente de `numB`.
       - `numA` ← `temp`
   - FIN TANT QUE

4. **Après la fin de la boucle, `numA` contient le PGCD.**
   - ÉCRIRE "Le PGCD est ", `numA`

### FIN
