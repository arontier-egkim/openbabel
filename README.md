# daverona/openbabel

[![pipeline status](https://gitlab.com/daverona/docker/openbabel/badges/master/pipeline.svg)](https://gitlab.com/daverona/docker/openbabel/commits/master)

This is a repository for Docker images of Open Babel library.

* GitLab source repository: [https://gitlab.com/daverona/docker/openbabel](https://gitlab.com/daverona/docker/openbabel)
* Docker Hub repository: [https://hub.docker.com/r/daverona/openbabel](https://hub.docker.com/r/daverona/openbabel)

Available versions are:

* [3.1.1](https://gitlab.com/daverona/docker/openbabel/-/blob/3.1.1/Dockerfile), [latest](https://gitlab.com/daverona/docker/openbabel/-/blob/latest/Dockerfile)
* [3.1.1-alpine3.10](https://gitlab.com/daverona/docker/openbabel/-/blob/3.1.1-alpine3.10/Dockerfile)
* [3.1.0](https://gitlab.com/daverona/docker/openbabel/-/blob/3.1.0/Dockerfile)
* [3.1.0-alpine3.10](https://gitlab.com/daverona/docker/openbabel/-/blob/3.1.0-alpine3.10/Dockerfile)
* [3.0.0](https://gitlab.com/daverona/docker/openbabel/-/blob/3.0.0/Dockerfile)
* [3.0.0-alpine3.10](https://gitlab.com/daverona/docker/openbabel/-/blob/3.0.0-alpine3.10/Dockerfile)

## Installation

Pull the image from Docker Hub repository:

```bash
docker image pull daverona/openbabel
```

## Quick Start

Run the container:

```bash
docker container run --rm \
  daverona/openbabel \
  python3 -c "import openbabel;print(openbabel.__version__)"
```

It will show the version of openbabel built in the container.

If you want a Python 3 shell with openbabel available, run the container:

```bash
docker container run --rm \
  --interactive --tty \
  daverona/openbabel
```

## References

* [https://github.com/openbabel/openbabel](https://github.com/openbabel/openbabel)
* [https://open-babel.readthedocs.io/en/latest/index.html](https://open-babel.readthedocs.io/en/latest/index.html)
