---

layout: post
title: utiliser un plugin traefik pour optimiser les images
category: architecture
---

Traefik a un systeme de plugins et une utilisation utile est de faire de l'optimisation des images.

Pour cela, le plugin observe un pattern d'urls et si ca correspond prend la main pour passer la requete
a un service [imaginary](https://github.com/h2non/imaginary) qui va retailler l'image.

Le plugin en question:
https://github.com/agravelot/traefik-image-optimization
