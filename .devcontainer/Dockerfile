FROM mcr.microsoft.com/devcontainers/cpp:0-ubuntu-22.04

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends bear clang-14 clangd-14 libaio1 libaio-dev \
    && apt-get -y install --no-install-recommends automake libtool pkg-config libattr1-dev libblkid-dev libselinux-dev udev libudev-dev uuid-dev meson \
    && sudo ln -s /usr/bin/clangd-14 /usr/bin/clangd

