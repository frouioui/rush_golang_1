# Exo 05

Nous allons appronfondir le principe des parametres dans les URLs, pour ca reprenez le code de l'exo 04.

Maintenant, quand nous accedons a notre route `/item/{id}` votre serveur doit etre capable d'accepter **uniquement** des nombres.

#### Exemple d'utilisation:
1. `localhost:8888/item/289`\
Doit afficher: `289`

2. `localhost:8888/item/jeSuisUneString`\
Doit envoyer une erreur `404`
