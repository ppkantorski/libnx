# Nintendo Switch AArch64-only userland library.
Based on libctru.

![Build status](https://github.com/switchbrew/libnx/actions/workflows/build.yaml/badge.svg)

# Install instructions
See [Switchbrew](https://switchbrew.org/wiki/Setting_up_Development_Environment).

```sh
make clean; make -j4
sudo -E make PREFIX=$DEVKITPRO/libnx install
````
