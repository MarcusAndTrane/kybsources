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

Ensuite plus qu'à aller voir sur [http://localhost:1313/sources4kyb/](http://localhost:1313/sources4kyb/)

## Et pour contribuer, mon con, on fait comment?
Et bah c'est très simple, personne très malpolie...
Toutes les cartes sont dans `./sources4kyb/data/items.toml`. Pour chaque carte, il suffit me modifier le champ `description = "ta source ici"`. Et par soucis de présentation, on pourrait partir sur des trucs de ce goût là:
```
"""
[1] la source numero 1 
<br>[2] la source numero 2
<br>[3] la source numero 3
"""
```

Pour un rendu comme ça:
```
[1] la source numero 1 
[2] la source numero 2
[3] la source numero 3
```

Je propose la convention [APA](http://www.bibme.org/citation-guide/apa/) pour le format des citations (American Psychology Association, TMTCBB)

Pour ce qui est du fonctionnement à proporement dit, rejoignez gitlab et le repo. Ensuite, pour les merge request, il y a un très bon [tuto dans la doc de GitLab](https://docs.gitlab.com/ee/gitlab-basics/add-merge-request.html)

## Pour la suite
Une fois qu'on est là, et que le job est terminé, pour une mise en prod il suffira de faire tout pareil, et rediriger le port 1313 avec NginX vers où on voudra!


## TODO
- ~~Caler les bonnes polices~~
