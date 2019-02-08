# Exo 14

Le JSON!!! Faisons un peu de JSON ensemble, mais tout d'abord qu'est ce que le JSON?\
Le JSON est un systeme de formattage des donnees particulier. Pour en apprendre plus je vous conseille ce [site](https://www.w3schools.com/whatis/whatis_json.asp).

On vous a donne en resource un fichier `./data.go` ce fichier contient un structure `Data`.
```go
    package main

    // Data ...
    type Data struct {
        Item      uint
        Value     string
        Corrupted bool
    }
```

Vous aller devoir creer une variable de type `Data` et lui assigner des valeurs:

Item | Value | Corrupted
---------|----------|---------
 4545 | "default" | true

Puis vous aller devoir transformer votre donnee en un JSON. Puis afficher le JSON sur votre terminal quand nous executons votre programme. Voici un exemple:

```shell
    $> go run main.go data.go | cat -e
    {"item":4545,"value":"default","invalid":true}$
```

Le nom des champs est case sensitive... les "[tags](https://medium.com/golangspec/tags-in-golang-3e5db0b8ef3e)" en Golang c'est vraiment genial.