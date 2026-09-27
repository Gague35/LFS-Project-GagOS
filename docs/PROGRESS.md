# LFS Build Progress

## Version

* **LFS:** 13.1
* **Architecture:** x86_64
* **Init:** SysVinit

---

## Preface

* [x] Foreword
* [x] Audience
* [x] LFS Target Architectures
* [x] Prerequisites
* [x] LFS and Standards
* [x] Package Rationale
* [x] Typographical Conventions
* [x] Structure
* [x] Errata and Security Advisories

---

# Part I — Introduction

## Chapter 1 — Introduction

* [x] How to Build an LFS System
* [x] What's New Since the Last Release
* [x] Changelog
* [x] Resources
* [x] Help

---

# Part II — Preparing for the Build

## Chapter 2 — Preparing the Host System

* [x] Introduction
* [x] Host System Requirements
* [x] Building LFS in Stages
* [x] Creating a New Partition
* [x] Creating a File System on the Partition
* [x] Setting the `$LFS` Variable and Umask
* [x] Mounting the New Partition

## Chapter 3 — Packages and Patches

* [x] Introduction
* [x] All Packages
* [x] Required Patches

## Chapter 4 — Final Preparations

* [x] Introduction
* [x] Creating a Limited Directory Structure in the LFS Filesystem
* [x] Adding the LFS User
* [x] Setting Up the Environment
* [x] About SBUs
* [x] About the Test Suites

---

# Part III — Building the LFS Cross-Toolchain and Temporary Tools

## Preliminary Information

* [x] Introduction
* [x] Toolchain Technical Notes
* [x] General Compilation Instructions

## Chapter 5 — Cross Compiling a Cross-Toolchain

* [x] Introduction
* [x] Binutils — Pass 1
* [x] GCC — Pass 1
* [x] Linux API Headers
* [x] Glibc
* [x] Libstdc++

## Chapter 6 — Cross Compiling Temporary Tools

* [x] Introduction
* [x] M4
* [x] Ncurses
* [x] Bash
* [x] Coreutils
* [x] Diffutils
* [x] File
* [x] Findutils
* [x] Gawk
* [x] Grep
* [x] Gzip
* [x] Make
* [x] Patch
* [x] Sed
* [x] Tar
* [x] Xz
* [x] Binutils — Pass 2
* [x] GCC — Pass 2

---

# Part IV — Building the LFS System

## Chapter 7 — Entering Chroot and Building Additional Temporary Tools

* [ ] Introduction
* [ ] Changing Ownership
* [ ] Preparing Virtual Kernel File Systems
* [ ] Entering the Chroot Environment
* [ ] Creating Directories
* [ ] Creating Essential Files and Symlinks
* [ ] Gettext
* [ ] Bison
* [ ] Perl
* [ ] Python
* [ ] Texinfo
* [ ] Util-linux
* [ ] Stripping and Saving the Temporary System

## Chapter 8 — Installing Basic System Software

* [ ] Introduction
* [ ] Package Management
* [ ] Man-pages
* [ ] Iana-Etc
* [ ] Glibc
* [ ] Zlib
* [ ] Bzip2
* [ ] Xz
* [ ] Lz4
* [ ] Zstd
* [ ] File
* [ ] Readline
* [ ] Pcre2
* [ ] M4
* [ ] Bc
* [ ] Flex
* [ ] Tcl
* [ ] Expect
* [ ] DejaGNU
* [ ] Pkgconf
* [ ] Binutils
* [ ] GMP
* [ ] MPFR
* [ ] MPC
* [ ] Attr
* [ ] Acl
* [ ] Libcap
* [ ] Libxcrypt
* [ ] Shadow
* [ ] GCC
* [ ] Ncurses
* [ ] Sed
* [ ] Psmisc
* [ ] Gettext
* [ ] Bison
* [ ] Grep
* [ ] Bash
* [ ] Libtool
* [ ] GDBM
* [ ] Gperf
* [ ] Expat
* [ ] Inetutils
* [ ] Less
* [ ] Perl
* [ ] XML::Parser
* [ ] Intltool
* [ ] Autoconf
* [ ] Automake
* [ ] OpenSSL
* [ ] Elfutils
* [ ] Libffi
* [ ] SQLite
* [ ] Python
* [ ] Flit-Core
* [ ] Packaging
* [ ] Wheel
* [ ] Setuptools
* [ ] Ninja
* [ ] Meson
* [ ] Kmod
* [ ] Coreutils
* [ ] Diffutils
* [ ] Gawk
* [ ] Findutils
* [ ] Groff
* [ ] GRUB
* [ ] Gzip
* [ ] IPRoute2
* [ ] Kbd
* [ ] Libpipeline
* [ ] Make
* [ ] Patch
* [ ] Tar
* [ ] Texinfo
* [ ] Vim
* [ ] MarkupSafe
* [ ] Jinja2
* [ ] Udev
* [ ] Man-DB
* [ ] Procps-ng
* [ ] Util-linux
* [ ] E2fsprogs
* [ ] Sysklogd
* [ ] SysVinit
* [ ] About Debugging Symbols
* [ ] Stripping
* [ ] Cleaning

## Chapter 9 — System Configuration

* [ ] Introduction
* [ ] LFS-Bootscripts
* [ ] Device and Module Handling
* [ ] Managing Devices
* [ ] General Network Configuration
* [ ] System V Boot Scripts
* [ ] System Locale Configuration
* [ ] Creating `/etc/inputrc`
* [ ] Creating `/etc/shells`

## Chapter 10 — Making the LFS System Bootable

* [ ] Introduction
* [ ] Creating `/etc/fstab`
* [ ] Linux
* [ ] Using GRUB to Set Up the Boot Process

## Chapter 11 — The End

* [ ] The End
* [ ] Registering
* [ ] Rebooting the System
* [ ] Additional Resources
* [ ] Beyond LFS

---

# Appendices

## Appendix A — Acronyms and Terms

* [ ] Complete

## Appendix B — Acknowledgments

* [ ] Complete

## Appendix C — Dependencies

* [ ] Complete

## Appendix D — Boot and System Configuration Scripts

* [ ] Review

## Appendix E — Udev Configuration Rules

* [ ] Review

## Appendix F — LFS Licenses

* [ ] Review

---

# Current Status

## Current Chapter

**Chapter 7 — Entering Chroot and Building Additional Temporary Tools**

## Last Completed Step

```text
GCC Pass 2
```

## Next Step

```text
Gettext
```

## Overall Progress

**Chapters 1–6 complete. Chapter 7 in progress.**
