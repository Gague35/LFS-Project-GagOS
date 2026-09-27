# Compilation Times

Compilation times measured during the construction of GagOS following the Linux From Scratch book.

> Only the most important and/or computationally significant packages are recorded here.
> Small or routine packages are intentionally omitted.

> **Reference SBU:** 23.648 seconds

SBU is calculated as:

```text
Measured SBU = real time / 23.648
```

## Chapter 5 — Cross-Toolchain

### Binutils Pass 1

* **LFS:** 1.0 SBU
* **Real:** 23.648 s
* **User:** —
* **Sys:** —
* **Measured SBU:** 1.00

### GCC Pass 1

* **LFS:** —
* **Real:** 2m46.566s
* **User:** 26m03.200s
* **Sys:** 1m16.775s
* **Measured SBU:** ≈ 7.04

### Glibc

* **LFS:** —
* **Real:** 49.660 s
* **User:** 7m08.813s
* **Sys:** 1m21.344s
* **Measured SBU:** ≈ 2.10

### Libstdc++

* **LFS:** —
* **Measured:** Not measured

## Chapter 6 — Temporary Tools

### Binutils Pass 2

* **LFS:** —
* **Measured:** Not measured

### GCC Pass 2

* **LFS:** —
* **Measured:** Not measured

## Chapter 7 — Entering the Chroot

### Gettext-1.0

* **LFS:** 1.5 SBU
* **Real:** 1m10.034s
* **User:** 2m16.558s
* **Sys:** 0m16.062s
* **Measured SBU:** ≈ 2.96

### Python-3.14.7

* **LFS:** 0.5 SBU
* **Real:** 0m16.521s
* **User:** 2m59.079s
* **Sys:** 0m7.285s
* **Measured:** ≈ 0.7

### Util-linux-2.42.2

* **LFS:** 0.2 SBU
* **Real:** 0m6.863s
* **User:** 1m10.934s
* **Sys:** 0m7.110s
* **Measured:** ≈ 0.29
