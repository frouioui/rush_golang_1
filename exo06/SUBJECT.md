# Exo 06

Package??? Nous allons creer notre premier package!!

Un package est un dossier contenant des fonctions, variables et des structures. Jusqu'a present vous avez code (normalement) dans le `package main`.

Pour specifier que vous coder dans un package particulier vous avez utiliser cette syntax:
```go
    package main
    
    func main() {
        // do something
    }
```

Nous allons changer ca en creant notre premier package `food`. Le dossier doit avoir le meme nom que le package, sinon votre code ne compilera pas.
```go
    package food

    // my awesome food package
```

Voila, c'etait une bref introduction au systeme de package de Golang, maintenant a votre tour... Creez un package `food` dans le dossier `./food/`. Ce package contiendra une **variable constante globale** de type _`int`_ avec une valeur de **42**, cette variable s'appelera "**DEFAULT**".\
Votre package aura egalement une function **public** `PrintMyStuff` qui affichera "**my stuff**" sur votre terminal.

> _En Golang, faire des packages permet d'avoir un code propre, maintenable et organiser. Il est fortement recomende d'utiliser des packages en plus de votre `package main` dans les prochain exercices. De plus, utiliser des package vous ferra toucher a des principes d'oriente objet_

----------

Ajoutez un main dans le package main puis testez votre code ;)

Pour tester votre projet la simple commande `go run main.go` devrait suffire ;) Voici un exemple :
```shell
    $> go run main.go | cat -e
    84$
    my stuff$
```
