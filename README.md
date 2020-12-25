# Sample commands to build and push images manually

## Build docker image

```
docker build -t node-chrome:latest .
```

## Create tag

```
docker tag node-chrome:latest puneetpunj/node-chrome:latest
```

## Push to Docker Registry

```
docker push puneetpunj/node-chrome:latest
```
