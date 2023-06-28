# static-files

## with index.html

```shell
# default port is 80
caddy file-server
# specify port
caddy file-server --listen :8083
```

## with browse

```shell
# default port is 80
caddy file-server --root /your/path --browse
# specify port
caddy file-server --listen :8083 --root /your/path --browse
```
