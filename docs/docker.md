# Docker

# Sauvegarder une image au format .tar
!!! info
    Il est nécessaire d'utiliser la commande `docker save`

```bash title="docker_save_tar" linenums="1"
docker save -o <file-name.tar> <image-name>:<tag>
```

# Sauvegarder une image au format .tar.gz
!!! info
    Il est nécessaire d'utiliser la commande `docker save` couplée à la commande `gzip`

```bash title="docker_save_tgz" linenums="1"
docker save <image-name>:<tag> | gzip > <file-name.tar.gz>
```

# Charger une image au format .tar
!!! info
    Il est nécessaire d'utiliser la commande `docker load`

```bash title="docker_load_tar" linenums="1"
docker load -i <file-name.tar>
```

# Charger une image au format .tar.gz
!!! info
    Il est nécessaire d'utiliser la commande `docker load`

```bash title="docker_load_tgz" linenums="1"
docker load < <file-name.tar.gz>
```