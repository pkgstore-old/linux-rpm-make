# Make

A GNU tool for controlling the generation of executables and other non-source files of a program from the program's source files. Make allows users to build and install packages without any significant knowledge about the details of the build process. The details about how the program should be built are provided for make in the program's makefile.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/build
$ dnf install -y make
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y make
```

## Remove

```
$ dnf erase -y make
$ dnf copr remove pkgstore/build
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/make).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/make) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
