# Exo 10

Continuons sur les methodes, nous allons maintenant jouer avec la methode `POST`.

Reprenez le serveur que vous avez cree dans l'exercice precedent, ajoutez-y la route `/user` qui accesible uniquement grace a une requette `POST`. La requette `POST` que votre serveur recevera contiendra deux champs: le premier "**name**" qui est une _`string`_, le second "**age**" qui est un _`int`_.

Quand vous recevez une requette `POST` sur cette route vous devrez en extraire les informations contenus dans les champs puis les afficher sur votre terminal comme ce ci:
```shell
    Name: {myName}
    Age: {myAge}
    New user added.
```
_Remplacez les `{}` par les valeurs recu dans la requette `POST`._

> _Utilisez gorilla mux ..._