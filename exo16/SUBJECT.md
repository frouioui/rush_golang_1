# Exo 16

Dans ce nouvel exercice vous aller recevoir du JSON dans le corps ("**body**") d'un requette.

Codez un serveur ecoutant sur le port `8000` avec une route `/user` accessible en `POST`. Le body de la requette contiendra du JSON, celui ci sera formate de la facon suivante:
```json
    {
        "human": {
            "alive": true,
            "age": 25
        }
    }
```

Recoder la structure permettant de contenir ces informations.\
Si l'age de l'humain que vous receverez dans la request est inferieur a 18, alors ecrivez "**mineur**" sur le terminal et dans le cas contraire ecrivez "**majeur**" sur le terminal.