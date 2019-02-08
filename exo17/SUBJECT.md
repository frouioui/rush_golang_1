# Exo 17

Voila.... vous etes ready! Maintenant codez une API REST entiere de vous meme.

### Voici les regles:

Port: `8888`

Routes:

URL | Methode | Action
---------|----------|---------
 `/` | `GET` | Affiche "**Good morning**" si c'est le matin et "**Good afternoon**" si c'est l'apres midi
 `/user` | `GET` | Renvoyer du JSON: `{"error":"no user found"}`
 `/user/{id}` | `DELETE` | Renvoyer du JSON: `{"message":"user {id} deleted"}`
 `/user` | `POST` | Receverez du JSON dans la requette contenant : `{"user":{"name":"randomName", "age":42}}`. Vous devrez renvoyer en JSON: `"user":"randomName", "added": true}`

C'est tout! Pour `/user/{id}` le `{id}` sera remplacer pas un _`int`_. Et pour `/user` en `POST`: "randomName" sera remplacer par une _`string`_ contenant un nom comme "Gildas" par exemple.