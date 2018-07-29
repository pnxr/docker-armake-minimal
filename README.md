Small Dockerimage with the latest version of [Armake] compiled from source master branch.

# Usage
Simple example of unpacking a file *mission.pbo* into subfolder *mission* of the current directory:
```bash
docker run -t -v $(pwd):/data -it pnxr/armake-minimal \
unpack /data/mission.pbo /data/mission
```

See also the [Full Syntax Documentation]

# Annotations
Thanks to [KoffeinFlummi] for creating his useful utillity which makes arma modding on linux way less painful.

[Armake]:https://github.com/KoffeinFlummi/armake
[Full Syntax Documentation]: https://github.com/KoffeinFlummi/armake#usage
[KoffeinFlummi]:https://github.com/KoffeinFlummi
