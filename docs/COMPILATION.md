# Compilation Times

Compilation times recorded during the construction of GagOS following the **Linux From Scratch** book.

> Only the most important and/or computationally significant packages are recorded here. Small or routine packages are intentionally omitted.

> **Reference SBU:** 23.648 seconds

SBU is calculated as:

```text
Measured SBU = real time / 23.648
```

Only the **Measured SBU** is retained for builds that were timed. No further build-time measurements will be recorded.

---

## Chapter 5 — Cross-Toolchain

### Binutils Pass 1

* **LFS:** 1.0 SBU
* **Measured SBU:** 1.00

### GCC Pass 1

* **LFS:** —
* **Measured SBU:** ≈ 7.04

### Glibc

* **LFS:** —
* **Measured SBU:** ≈ 2.10

### Libstdc++

* **LFS:** —
* **Measured:** Not measured

---

## Chapter 6 — Temporary Tools

### Binutils Pass 2

* **LFS:** —
* **Measured:** Not measured

### GCC Pass 2

* **LFS:** —
* **Measured:** Not measured

---

## Chapter 7 — Entering the Chroot

### Gettext-1.0

* **LFS:** 1.5 SBU
* **Measured SBU:** ≈ 2.96

### Python-3.14.7

* **LFS:** 0.5 SBU
* **Measured SBU:** ≈ 0.70

### Util-linux-2.42.2

* **LFS:** 0.2 SBU
* **Measured SBU:** ≈ 0.29

---

## Chapter 8 — Base System

### Glibc-2.44

* **LFS:** 11 SBU
* **Measured SBU:** ≈ 0.21

### Binutils-2.47

* **LFS:** 1.7 SBU
* **Measured:** Not measured

### GCC-16.2.0

* **LFS:** 53 SBU (with tests)
* **Measured:** Not measured

### Ncurses-6.6

* **LFS:** 0.2 SBU
* **Measured:** Not measured

### Perl-5.44.0

* **LFS:** 1.3 SBU
* **Measured:** Not measured

### OpenSSL-4.0.1

* **LFS:** 1.9 SBU
* **Measured:** Not measured

### Python-3.14.7

* **LFS:** 2.7 SBU
* **Measured:** Not measured

### GRUB-2.14

* **LFS:** 1.0 SBU
* **Measured:** Not measured

### Util-linux-2.42.2

* **LFS:** 0.5 SBU
* **Measured:** Not measured

### E2fsprogs-1.47.4

* **LFS:** 0.4 SBU (SSD) / 2.4 SBU (HDD)
* **Measured:** Not measured
