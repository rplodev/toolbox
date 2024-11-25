# Docker - Sauvegarde d'images

## Sauvegarder une image au format .tar
!!! tip
    Il est nécessaire d'utiliser la commande `docker save`

```bash
docker save -o <file-name.tar> <image-name>:<tag>
```

## Sauvegarder une image au format .tar.gz
!!! tip
    Il est nécessaire d'utiliser la commande `docker save` couplée à la commande `gzip`

```bash
docker save <image-name>:<tag> | gzip > <file-name.tar.gz>
```
