## About

This uses the [`alpine`](https://hub.docker.com/_/alpine) as base images.

### Pre-built image

[![Docker Pulls](https://img.shields.io/docker/pulls/libreofficedocker/libreoffice-unoserver)](https://hub.docker.com/r/libreofficedocker/libreoffice-unoserver)

You can find the pre-built images on [Docker Hub](https://hub.docker.com/u/libreofficedocker).

### REST API

This image do not shipped with REST API for unoserver by default.

Please use https://github.com/libreoffice-docker/unoserver-rest-api.

### Environment Variables

| Variable      | Default   | Required | Description               |
| ------------- | --------- | -------- | ------------------------- |
| UNOSERVER_CMD | unoserver |          | Set the unoserver command |

## License

Licensed under [Apache-2.0 license](LICENSE)
