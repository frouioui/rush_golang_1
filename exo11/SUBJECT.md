# Exo 11

Abordons maintenant la methode `DELETE`...

> _Si vous ne connaissez pas les methodes renseignez vous sur le cas d'utilisation de chacun avant de coder bettement ;)_

Reprenez le code de l'exercice precedent. Ajouter un route `/user/{id}` qui est uniquement accesible par la methode `DELETE`. Quand nous appelons la methode votre serveur doit afficher la ligne suivante :
```shell
    user {id} deleted
```

> _Utilisez gorilla mux ..._