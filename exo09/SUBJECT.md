# Exo 09

Nous allons a present parler des differentes methodes. (`GET`, `POST`, `DELETE`, `PATCH`...).\
Pour plus d'info clickez [ici](https://developer.mozilla.org/fr/docs/Web/HTTP/M%C3%A9thode).

Nous allons creer un serveur ecoutant sur le port `8080`. Creer une route `/` qui sera accessible **uniquement** par une requette `GET`. Une requette `POST` ou autre que `GET` ne pourra pas acceder a cette route.

> _Utilisez gorilla mux ..._