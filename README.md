# TurboArtix -- A systemd-less alternative to TurboArch
This script allows you to replace any Linux distribution with Artix Linux, preserving user data and some system configuration. 

> [!NOTE]
> This project is still under the development stage and may or may not work right now.

## Quick start
Download and run required scripts:
```
git clone https://github.com/AFellowSpeedrunner/turboartix
cd turboartix
sudo bash turboartix.sh
```
This will ask some questions and begin the Artix installation. Data in `/home`, disk configuration (even with LVM and LUKS!), user accounts and passwords, sudo/wheel group will be preserved.

> [!IMPORTANT]
> Everything in `/bin`, `/boot`, `/etc`, `/lib`, `/lib64`, `/sbin`, `/srv`, `/usr` and `/var` will be permanently removed. Other directories will not be affected at all, and no partitions will be formatted.

## Requirements
* Internet connection
* x86_64 Linux kernel version suitable for glibc in Artix (3.2+ for glibc version 2.39)
* `grep`, `coreutils` and `util-linux`
* `bash` version 4+
* `wget` or `curl` to download the Artix bootstrap, `tar` and `xz` to decompress bootstrap archive.

## The installation process
If we get the project to actually be installable we'll write how this works under this section.

## Tested distributions
None so far.
