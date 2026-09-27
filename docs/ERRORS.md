# Errors & Issues

## LFS-Bootscripts

### Problem

The `lfs-bootscripts-20250827.tar.xz` archive obtained from the initial mirror did not match the expected MD5 checksum.

Expected MD5:

```text
1202731e161e2a65d74a9ce051ed0242
```

### Resolution

The correct archive was eventually downloaded from a working LFS mirror.

The archive was then verified using `md5sum -c md5sums`.

### Status

Resolved.

## Grep / Sed

### Problem

`grep` and `sed` were missing from the LFS environment when building `gettext` in Chapter 7.

### Resolution

The programs had been built during Chapter 6 but were not correctly installed into `$LFS/usr`.

They were reinstalled as `root` using:

```bash
make DESTDIR=$LFS install
```

### Status

Resolved.

