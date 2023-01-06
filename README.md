# Docker Images

[![.github/workflows/push.yml](https://github.com/alexandru/docker-images/actions/workflows/push.yml/badge.svg)](https://github.com/alexandru/docker-images/actions/workflows/push.yml)

Personal Docker images that I need as a baseline for other things.

| Image | Build | Description |
|------------|------|-------------|
| ghcr.io/alexandru/jdk-build-tools:latest | [Dockerfile](./Dockerfile.jdk-build-tools) | Meant for building JVM projects, has OpenJDK installed with all the build tools (sbt, gradle, maven, scalacli, jbang) |
| ghcr.io/alexandru/jre17-minimal-debian:latest | [Dockerfile](./Dockerfile.jre17-minimal-debian) | Very slim image with JRE17 installed, based on Debian. |
| ghcr.io/alexandru/jre17-minimal-alpine:latest | [Dockerfile](./Dockerfile.jre17-minimal-alpine) | Very slim image with JRE17 installed, based on Alpine. |
