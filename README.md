# Turi Create Image
[![Docker Pulls](https://img.shields.io/docker/pulls/skiphoutzager/turicreate.svg?style=round-square)](https://hub.docker.com/r/skiphoutzager/turicreate/)
[![](https://images.microbadger.com/badges/image/skiphoutzager/turicreate.svg)](https://microbadger.com/images/skiphoutzager/turicreate "Get your own image badge on microbadger.com")

This repository contains a Docker image for running Turi Create scripts.

# Usage
```bash
docker run --rm -v /my/volume/directory/:/workdir/ skiphoutzager/turicreate python some_python_file.py
```

The run configuration example described above could be used for running a Turi Create script located in your workdir. The container will remove itself as soon as it's finished.

# References
Docker Hub: https://hub.docker.com/r/skiphoutzager/turicreate

Turi Create Repo: https://github.com/apple/turicreate