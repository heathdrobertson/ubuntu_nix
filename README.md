# Ubuntu with Nix
__A `Nix` environment running on an Ubuntu Docker image.__


With a `defualt.nix` file in your current working dirrectory, create a docker container:

```bash
export CONTAINER_NAME=<change_me>
```

```bash
docker run -it \
--name ${CONTAINER_NAME} \
--volume $(pwd):/home/ci  \
heathrobertson/nix
```


## heathrobertson/nix:latest



