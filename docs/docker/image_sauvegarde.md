# Docker - Sauvegarde d'images

## Sauvegarder une image au format .tar
!!! info
    Il est nécessaire d'utiliser la commande `docker save`

```bash title="docker_save_tar" linenums="1"
docker save -o <file-name.tar> <image-name>:<tag>
```

## Sauvegarder une image au format .tar.gz
!!! info
    Il est nécessaire d'utiliser la commande `docker save` couplée à la commande `gzip`

```bash title="docker_save_tgz" linenums="1"
docker save <image-name>:<tag> | gzip > <file-name.tar.gz>
```
