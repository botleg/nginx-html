NGINX html
===

This repository contains the code for the docker image, [hanzel/nginx-html](https://hub.docker.com/r/hanzel/nginx-html/). The image is based on `Alpine` linux and contains `nginx` webserver. The webserver serves the `index.html` file.

Docker Compose
---

Sample docker-compose.yml configuration is given below:

```
version: '2'

services:
  web:
    image: nginx-html
    ports:
      - "80"
```