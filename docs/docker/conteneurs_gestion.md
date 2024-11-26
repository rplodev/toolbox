# Docker - Gestion des conteneurs

## Créer et lancer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run <image>
```
Ou
``` bash
docker run <image>:<tag>latest
```

## Créer et lancer un conteneur nommé
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -n <nom_conteneur> <image>
```
Ou
``` bash
docker run -n <nom_conteneur> <image>:<tag>latest
```

## Créer et lancer un conteneur en mode détaché (en background)
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -d <image>
```
Ou
``` bash
docker run -d <image>:<tag>latest
```

## Créer et lancer un conteneur en mode terminal interactif
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -it <image> <path_shell>
```
Ou
``` bash
docker run -d <image>:<tag>latest <path_shell>
```

## Créer et lancer un conteneur en mode terminal interactif
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -it <image> <path_shell>
```
Ou
``` bash
docker run -d <image>:<tag>latest <path_shell>
```

## Démarrer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker start`

``` bash
docker run start <nom_conteneur>
```

## Arrêter un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker stop`

``` bash
docker run stop <nom_conteneur>
```

## Forcer l'arrêt d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker kill`

``` bash
docker run kill <nom_conteneur>
```

## Redémarrer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker restart`

``` bash
docker run restart <nom_conteneur>
```

## Supprimer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker rm`

``` bash
docker run rm <nom_conteneur>
```

## Supprimer un conteneur en cours de fonctionnement
!!! tip
    Il est nécessaire d'utiliser la commande `docker rm`

``` bash
docker run rm -f <nom_conteneur>
```

## Exécuter une commande dans un conteneur démarré en mode détaché
!!! tip
    Il est nécessaire d'utiliser la commande `docker exec`

``` bash
docker run exec <nom_conteneur> <path_commande>
```

## Lancer un terminal dans un conteneur démarré en mode détaché
!!! tip
    Il est nécessaire d'utiliser la commande `docker exec`

``` bash
docker run exec -it <nom_conteneur> <path_shell>
```

## Lister les conteneurs actifs
!!! tip
    Il est nécessaire d'utiliser la commande `docker ps`

``` bash
docker run ps
```

## Lister l'intégralité des conteneurs
!!! tip
    Il est nécessaire d'utiliser la commande `docker ps`

``` bash
docker run ps -a
```

## Afficher les logs d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker logs`

``` bash
docker run logs <nom_conteneur>
```

## Afficher en temps réel les logs d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker logs`

``` bash
docker run logs -f <nom_conteneur>
```

## Attacher un conteneur en cours de fonctionnement
!!! tip
    Il est nécessaire d'utiliser la commande `docker attach`

``` bash
docker run attach <nom_conteneur>
```