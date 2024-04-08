# Programme de Comparaison de Deux Valeurs Numériques

Ce programme compare deux valeurs numériques fournies par l'utilisateur et indique leur relation : si elles sont égales, si la première est plus grande que la seconde, ou si la première est plus petite que la seconde.

## Déclaration des Variables

- `valA` et `valB` sont les deux valeurs numériques à comparer.

Type des variables `valA`, `valB` : nombre

## Algorithme

### DÉBUT

1. **Demande à l'utilisateur d'entrer la première valeur.**
   - ÉCRIRE "Saisissez la première valeur numérique"
   - LIRE `valA`
   
2. **Demande à l'utilisateur d'entrer la seconde valeur.**
   - ÉCRIRE "Saisissez la seconde valeur numérique"
   - LIRE `valB`

3. **Compare les deux valeurs et traite les trois cas possibles.**
   - SI `valA` = `valB` ALORS
     - ÉCRIRE "Les deux valeurs sont égales."
   - SINON SI `valA` > `valB` ALORS
     - ÉCRIRE "La première valeur est plus grande que la seconde."
   - SINON
     - ÉCRIRE "La première valeur est plus petite que la seconde."
   - FIN SI

### FIN
