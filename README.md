# LFS-Project-GagOS

**GagOS** is a personal Linux distribution project built from [Linux From Scratch](https://www.linuxfromscratch.org/lfs/).

The goal is to build a complete Linux system from scratch, understand how its different components work, and progressively turn the LFS base system into a personal Linux distribution.

## Current Build

* **LFS:** 13.1
* **Architecture:** x86_64
* **Init system:** SysVinit
* **Status:** LFS Chapter 7

The current build follows the **LFS 13.1 SysVinit** book. A systemd-based build may be explored later.

## Documentation

Project-specific documentation is available in [`docs/`](docs/):

* [Build Environment](docs/BUILD.md) — Build environment and configuration
* [Hardware & Virtual Machine](docs/HARDWARE.md) — Hardware and VM configuration
* [Build Progress](docs/PROGRESS.md) — Progress through the LFS book
* [Compilation Times](docs/COMPILATION.md) — Build times and SBU measurements
* [Errors & Issues](docs/ERRORS.md) — Errors encountered during the build
* [Design Decisions](docs/DECISIONS.md) — Important project decisions and changes

## References

### Linux From Scratch 13.1

#### SysVinit

* [English](https://www.linuxfromscratch.org/lfs/view/stable/)
* [Français](https://www.fr.linuxfromscratch.org/view/lfs-stable/)

#### systemd

* [English](https://www.linuxfromscratch.org/lfs/view/stable-systemd/)
* [Français](https://www.fr.linuxfromscratch.org/view/lfs-systemd/)

### Beyond Linux From Scratch 13.1

BLFS extends an LFS system with additional software and functionality. It will be considered after completing the LFS base system.

#### SysVinit

- [English — Latest stable version](https://www.linuxfromscratch.org/blfs/view/stable/)
- [Français — 13.1](https://fr.linuxfromscratch.org/view/blfs-13.1-fr/)

> The English BLFS SysVinit branch is currently maintained at version 12.4, while the French translation provides BLFS 13.1.

#### systemd

- [English — 13.1](https://www.linuxfromscratch.org/blfs/view/13.1-systemd/)
- [Français — 13.1](https://fr.linuxfromscratch.org/view/blfs-systemd-stable/)

## Roadmap

* [x] Prepare the LFS build environment
* [x] Build the cross-toolchain
* [x] Build the temporary tools
* [ ] Complete the LFS system
* [ ] Decide on the future GagOS base
* [ ] Extend the system with BLFS
* [ ] Add GagOS-specific configuration and software
* [ ] Develop GagOS beyond the standard LFS/BLFS system

## License

See [`LICENSE`](LICENSE).
