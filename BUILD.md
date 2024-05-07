# Uploading

```
podman run -v $PWD:/code:ro -v steamcmd-data:/data -v steamcmd-root:/root/.local/share/Steam -it steamcmd/steamcmd:debian-12 \
  +login $STEAMUSER +workshop_build_item /code/steamcmd.txt +quit
```
