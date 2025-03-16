## dockerfiles

[![make test](https://img.shields.io/github/actions/workflow/status/yakir3/gitbook/main.yml?label=actions&logo=github&logoColor=white)](https://github.com/yakir3/gitbook/actions/workflows/)


This is a repo to hold various Dockerfiles for images.


**Table of Contents**

<!-- toc -->

- [Resources](#resources)
  * [Using the `Makefile`](#using-the-makefile)

<!-- tocstop -->

## Resources
### Using the `Makefile`

```
$ make help
all                            Build all and push
build                          Builds all the dockerfiles in the repository.
image                          Build a Dockerfile (ex. DIR=network-tools).
run                            Run a Dockerfile from the command at the top of the file (ex. DIR=system-tools).
test                           Run the tests
```

> Fork from: https://github.com/jessfraz/dockerfiles
