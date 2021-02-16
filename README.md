# greencore-docker
Dockerfiles for containers that Greencore published to hub.docker.com

## How to

This is how to upload images to hub.docker.com. Please note that your user has to be associated with the organization ``greencorecr``.

```bash
docker tag 7f5917a813a9 nginx_modsecurity:latest  #This is the ID of the recently build image
docker image tag nginx_modsecurity:latest greencorecr/nginx_modsecurity:latest
docker image push greencorecr/nginx_modsecurity:latest
```

