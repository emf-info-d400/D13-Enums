# Devoir 13 : Enums

Voici un exercice en Java qui te permettra de pratiquer avec les énumérations (enums). L'exercice se divise en deux parties : la définition d'une énumération et son utilisation.

## Consigne

Créer une application Java qui utilise des énumérations pour gérer différents états d'un objet `Commande` dans un système de gestion de commandes.

1. Dans le package `models`, définis un nouveau fichier représentant une énumération nommée `EtatCommande`. Cette énumération représentera les différents états possibles d'une commande dans le système. Les états possibles sont : `EN_ATTENTE`, `TRAITEMENT_EN_COURS`, `EXPEDIEE`, `LIVREE`. Tu peux lire la documentation pour t'aider à créer ce nouvel élément Java : https://www.w3schools.com/java/java_enums.asp
   
2. Crée une classe `Commande`. Cette classe doit contenir deux propriétés : un identifiant unique pour la commande sous forme de texte et l'état de la commande (en utilisant l'énumération `EtatCommande`).

3. Dans la classe `Commande`, ajoute une méthode qui changera l'état de la commande à l'état suivant dans le cycle de vie d'une commande (par exemple, de `EN_ATTENTE` à `TRAITEMENT_EN_COURS`, etc.). Si la commande est dans l'état `LIVREE`, son état ne change pas.

4. Ajoute une méthode à la classe `Commande` lui donnant la capacité d'afficher l'état actuel de la commande. Voici un exemple d'affichage d'une commande :
```
Commande{id='CMD123', etat=LIVREE}
```

5. Dans la méthode principale (`main`), crée une instance de la classe `Commande`. Change son état plusieurs fois et affiche l'état de la commande après chaque changement.

## RESTITUTION
Rendre ce devoir normalement par push GitHub