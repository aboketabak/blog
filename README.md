# Blog Minitel — GitHub Pages

Blog minimaliste style Minitel généré avec Jekyll.

## Structure

```
_config.yml         Configuration Jekyll
_posts/             Articles (format AAAA-MM-JJ-titre.md)
assets/css/         Style Minitel personnalisé
about.md            Page à propos
index.md            Page d'accueil
```

## Mise en ligne

1. Crée un repo GitHub nommé `PSEUDO.github.io`
2. Dépose tous ces fichiers à la racine
3. Va dans Settings > Pages > Deploy from branch > main
4. Ton blog est en ligne à `https://PSEUDO.github.io`

## Ajouter un article

Crée un fichier dans `_posts/` nommé :
`AAAA-MM-JJ-mon-titre.md`

Avec cet en-tête :
```
---
layout: post
title: "Titre de l'article"
date: AAAA-MM-JJ
categories: scripts
---
```
