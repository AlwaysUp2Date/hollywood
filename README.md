# Docker image for hollywood

## About AlwaysUp2Date
AlwaysUp2Date is an organization that creates trusted Docker images for a variety of different programs that don't provide official images. All Docker images from `AlwaysUp2Date` updated automatically (so that you can get your security patches asap) and built directly on Docker Hub servers for maximum trust and transparency. You can verify the exact Dockerfiles that have been used for each build directly on Docker Hub. 

## Examples

### With default settings:

```
docker run -ti alwaysup2date/hollywood
```

### With custom settings:

```
docker run -ti alwaysup2date/hollywood hollywood --delay 5 --splits 7
```
