FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install android-tools-adb
RUN usermod -aG plugdev node