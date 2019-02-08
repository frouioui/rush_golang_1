# Exo 04

Dans ce nouvel exercice nous verrons comment recevoir des parametres dans nos URLs.

Creez un serveur ecoutant sur le port `8888`, ce serveur contient deux routes. La premiere `/user/{name}` et la seconde `/item/{id}`. Chacune de ces routes recevera un nom (une _string_) pour `{name}` et un ID (un _int_) pour `{id}`.

Quand nous accedons aux URLs vous devrez repondre en affichant la valeur du paramete `{name}` ou `{id}` sur la page du navigateur internet.

#### Exemple d'utilisation:
`localhost:8888/item/289`\
Doit afficher: `289`
