# Docker - Gestion des conteneurs

## Créer et lancer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run <image>
```
Ou
``` bash
docker run <image>:<tag>
```

## Créer et lancer un conteneur nommé
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -n <nom_conteneur> <image>
```
Ou
``` bash
docker run -n <nom_conteneur> <image>:<tag>
```

## Créer et lancer un conteneur en mode détaché (en background)
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -d <image>
```
Ou
``` bash
docker run -d <image>:<tag>
```

## Créer et lancer un conteneur en mode terminal interactif
!!! tip
    Il est nécessaire d'utiliser la commande `docker run`

``` bash
docker run -it <image> <path_shell>
```
Ou
``` bash
docker run -it <image>:<tag> <path_shell>
```

## Démarrer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker start`

``` bash
docker start <nom_conteneur>
```

## Arrêter un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker stop`

``` bash
docker stop <nom_conteneur>
```

## Forcer l'arrêt d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker kill`

``` bash
docker kill <nom_conteneur>
```

## Redémarrer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker restart`

``` bash
docker restart <nom_conteneur>
```

## Supprimer un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker rm`

``` bash
docker rm <nom_conteneur>
```

## Supprimer un conteneur en cours de fonctionnement
!!! tip
    Il est nécessaire d'utiliser la commande `docker rm`

``` bash
docker rm -f <nom_conteneur>
```

## Supprimer les conteneurs inutilisées
!!! tip
    Il est nécessaire d'utiliser la commande `docker container`

``` bash
docker container prune
```

## Exécuter une commande dans un conteneur démarré en mode détaché
!!! tip
    Il est nécessaire d'utiliser la commande `docker exec`

``` bash
docker exec <nom_conteneur> <path_commande>
```

## Lancer un terminal dans un conteneur démarré en mode détaché
!!! tip
    Il est nécessaire d'utiliser la commande `docker exec`

``` bash
docker exec -it <nom_conteneur> <path_shell>
```

## Lister les conteneurs actifs
!!! tip
    Il est nécessaire d'utiliser la commande `docker ps`

``` bash
docker ps
```

## Lister l'intégralité des conteneurs
!!! tip
    Il est nécessaire d'utiliser la commande `docker ps`

``` bash
docker ps -a
```

## Afficher les logs d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker logs`

``` bash
docker logs <nom_conteneur>
```

## Afficher en temps réel les logs d'un conteneur
!!! tip
    Il est nécessaire d'utiliser la commande `docker logs`

``` bash
docker logs -f <nom_conteneur>
```

## Attacher un conteneur en cours de fonctionnement
!!! tip
    Il est nécessaire d'utiliser la commande `docker attach`

``` bash
docker attach <nom_conteneur>
```

## Afficher les processes en cours pour un container
!!! tip
    Il est nécessaire d'utiliser la commande `docker top`

``` bash
docker top <nom_conteneur>
```