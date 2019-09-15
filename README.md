# KYB Sources
La code du site pour KYB.
Le thème a été créé par [Pavel Kanyshev](https://github.com/aerohub), en se basant sur [cet article de Codrops](http://tympanus.net/codrops/2013/03/19/thumbnail-grid-with-expanding-preview/).

C'est un site statique qui repose sur [Hugo](http://gohugo.io).

## Installation de Hugo
### Install sous OSX 
Si c'est pas déjà fait installez [Homebrew](https://brew.sh/index_fr) pour commencer... Et ensuite: 
```
brew install hugo
```
*IZI PIZI LEMON SQUIZY*

### Install sous Windows comme Tom
Je sais pas trop comment ça marche, mais il y a un tuto dans la doc [ICI](https://gohugo.io/getting-started/installing/#windows)

## Pecho le site en local...

```
git clone https://gitlab.com/Wyoc/sources4kyb.git
cd sources4kyb
```

## et lancer le serveur!

```
hugo server
```

Ensuite plus qu'à aller voir sur [http://localhost:1313/](http://localhost:1313/)

## Pour la suite
Une fois qu'on est là, et que le job est terminé, pour une mise en prod il suffira de faire tout pareil, et rediriger le port 1313 avec NginX vers où on voudra!

