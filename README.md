# Docker-Jira

[![](https://img.shields.io/docker/cloud/build/kitsdq/jira.svg)](https://hub.docker.com/r/kitsdq/jira/builds)
[![](https://img.shields.io/github/tag/kit-sdq/Docker-Jira.svg)](https://hub.docker.com/r/kitsdq/jira/tags)
[![](https://img.shields.io/github/issues/kit-sdq/Docker-Jira.svg)](https://github.com/kit-sdq/Docker-Jira/issues)
[![](https://img.shields.io/github/license/kit-sdq/Docker-Jira.svg)](https://github.com/kit-sdq/Docker-Jira/blob/master/LICENSE)

Docker image for [Atlassian JIRA](https://www.atlassian.com/software/jira) that includes a recent [MySQL connector](https://dev.mysql.com/downloads/connector/j/5.1.html) and AdoptOpenJDK 11.

JIRA is running under user `jira` with uid `1432`. The home directory is `/var/jira`.

Docker images are available on [DockerHub](https://hub.docker.com/r/kitsdq/jira).