# docker-armake-minimal

Small Dockerimage with the latest version of [Armake] compiled from source master branch hosted at [Docker Hub].

## Usage
Simple example of unpacking a pbo file *mission.pbo* into subfolder *mission* of the current directory with this image:
```bash
docker run -t -v $(pwd):/data -it pnxr/armake-minimal unpack /data/mission.pbo /data/mission
```
See also the [Full Syntax Documentation]

## Annotations
Thanks to [KoffeinFlummi] for creating his useful utillity which makes arma modding on linux way less painful.

[Docker Hub]:https://hub.docker.com/r/pnxr/armake-minimal/
[Armake]:https://github.com/KoffeinFlummi/armake
[Full Syntax Documentation]: https://github.com/KoffeinFlummi/armake#usage
[KoffeinFlummi]:https://github.com/KoffeinFlummi
