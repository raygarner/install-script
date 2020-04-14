# Arch install script

## Usage:
```
./init
./post-chroot
exit
umount -R /mnt
reboot
```

## Disk partitions
This script expects you to make 2 partitions when fdisk is launched:

* Swap partition
* filesystem partition

Remember the number you give each partition
