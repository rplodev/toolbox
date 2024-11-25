# Docker - Gestion des images

## Télécharger la version latest d'une image depuis un registre Docker
!!! tip
    Il est nécessaire d'utiliser la commande `docker pull`

``` bash
docker pull <image>
```
Ou
``` bash
docker pull <image>:latest
```

## Télécharger la version spécifique d'une image depuis un registre Docker
!!! tip
    Il est nécessaire d'utiliser la commande `docker pull`

``` bash
docker pull <image>:<tag>
```

## Lister les images présentes dans le système
!!! tip
    Il est nécessaire d'utiliser la commande `docker images`

``` bash
docker images
```

## Supprimer une image tagguée latest présente dans le système
!!! tip
    Il est nécessaire d'utiliser la commande `docker rmi`

``` bash
docker rmi <image>
```
Ou
``` bash
docker rmi <image>:latest
```

## Supprimer une image avec un tag spécifique présente dans le système
!!! tip
    Il est nécessaire d'utiliser la commande `docker rmi`

``` bash
docker rmi <image>:<tag>
```

## Construire une image sans tag spécifique
!!! tip
    Il est nécessaire d'utiliser la commande `docker build`

``` bash
docker build -t <nom_image> <emplacement_du_Dockerfile>
```

## Construire une image avec tag spécifique
!!! tip
    Il est nécessaire d'utiliser la commande `docker build`

``` bash
docker build -t <nom_image>:<tag> <emplacement_du_Dockerfile>
```

## Renommer une image présente dans le système
!!! tip
    Il est nécessaire d'utiliser la commande `docker tag`

``` bash
docker tag -t <nom_image_source>:<tag_source> <nom_image_destination>:<tag_source>
```

## Ajouter/Modifier le tag d'une image présente dans le système
!!! tip
    Il est nécessaire d'utiliser la commande `docker tag`

``` bash
docker tag -t <nom_image_source>:<tag_source> <nom_image_source>:<tag_destination>
```

## Sauvegarder une image au format .tar
!!! tip
    Il est nécessaire d'utiliser la commande `docker save`

``` bash
docker save -o <file-name.tar> <image-name>:<tag>
```

## Sauvegarder une image au format .tar.gz
!!! tip
    Il est nécessaire d'utiliser la commande `docker save` couplée à la commande `gzip`

``` bash
docker save <image-name>:<tag> | gzip > <file-name.tar.gz>
```

## Charger une image au format .tar
!!! tip
    Il est nécessaire d'utiliser la commande `docker load`

``` bash
docker load -i <file-name.tar>
```

## Charger une image au format .tar.gz
!!! tip
    Il est nécessaire d'utiliser la commande `docker load`

``` bash
docker load < <file-name.tar.gz>
```