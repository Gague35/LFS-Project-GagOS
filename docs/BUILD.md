# Build Environment

## LFS Directory

```text
/mnt/lfs
```

Environment variable:

```bash
export LFS=/mnt/lfs
```

Sources:

```text
/mnt/lfs/sources
```

## Build User

The temporary `lfs` user is used during the build stages where required by the LFS book.

Switch to `lfs`:

```bash
su - lfs
```

Switch to `root`:

```bash
su -
```

## Parallel Compilation

```bash
export MAKEFLAGS=-j$(nproc)
```

Number of available CPU cores:

```bash
nproc
```

Current build configuration:

```text
12 CPU cores
```

## Architecture

```text
x86_64
```

## Dynamic Linker

```text
ld-linux-x86-64.so.2
```

Verified with:

```bash
readelf -l /bin/bash | grep interpreter
```

## Host Requirements

The host system must meet the requirements specified by the LFS book, including:

* Bash and `/bin/sh`
* `awk` → `gawk`
* `yacc` → `bison`
* Required build tools
* Required libraries

Check `/bin/sh`:

```bash
ls -l /bin/sh
```

Check `awk`:

```bash
ls -l /usr/bin/awk
awk --version
```

Check `yacc`:

```bash
ls -l /usr/bin/yacc
yacc --version
```

## Source Organization

Sources are stored in:

```text
/mnt/lfs/sources
```

Source archives are extracted using `tar`, as required by the LFS book.

Source directories are removed after use when instructed by the LFS book.
