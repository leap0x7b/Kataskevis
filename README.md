# Kataskevis
A simple build system made in Bash shell script

## How does it work?
Kataskevis generates build files from your Kataskevisfile to be built with Make (and soon Ninja). This is similar to what CMake and Meson does, but in pure shell script. Kataskevisfile is a simple shell script to configure Kataskevis build files, similiar to how makepkg works by using PKGBUILD which also a simple shell script to configure makepkg.

## Installation
It's very simple. Just download `kataskevis` from this Git repository to your /usr/local/bin directory.
```bash
$ curl -L https://git.io/kataskevis > /usr/local/bin/kataskevis
$ chmod +x /usr/local/bin/kataskevis
```

## Progress
- [X] Make a simple build system
- [ ] Add options support
- [ ] Add Ninja support
