# SSLyze, Dockerized

SSL scanning, made easy. This repository is the [SSLyze](https://github.com/nabla-c0d3/sslyze) tool wrapped up in a Docker container, so you don't have to fuss with installing things like Python or development headers.

## Usage

Requires [Docker](https://www.docker.com/).

```bash
docker run 18fgsa/sslyze
```

This will print out the usage instructions. Arguments can then be appended to the command, like so:

```bash
docker run 18fgsa/sslyze --regular mysite.com
```
