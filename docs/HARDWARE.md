# Hardware & Virtual Machine

## Host Machine

* **CPU:** Intel Core i5-14600KF
* **RAM:** 32 GB
* **Host OS:** Debian

## Virtual Machine

* **Hypervisor:** Hyper-V
* **CPU:** 12 vCPU
* **RAM:** 12 GB
* **Dynamic Memory:** Disabled

## LFS Storage

* **Disk size:** 60 GB
* **Filesystem:** ext4
* **Mount point:** `/mnt/lfs`

## VM Configuration

The LFS system is built inside a dedicated virtual machine.

The VM resources can be adjusted depending on the requirements of the build.

> The LFS disk may appear under different device names depending on the VM configuration. The filesystem should therefore be identified using its UUID in `/etc/fstab` rather than relying on `/dev/sda`, `/dev/sdb`, etc.

To check the available disks:

```bash
lsblk -f
```

## Changing VM Resources

To change the number of vCPUs or the amount of RAM:

1. Completely shut down the VM.
2. Change the settings in Hyper-V.
3. Start the VM again.

A saved state may prevent some hardware settings from being changed.
