FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install android-tools-adb
RUN usermod -aG plugdev node

# ENV ADB_IP="192.168.1.1"
# ENV REACT_NATIVE_PACKAGER_HOSTNAME="192.255.255.255"