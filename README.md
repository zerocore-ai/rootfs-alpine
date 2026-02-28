# rootfs-alpine

Alpine Linux v3.23 root filesystem for aarch64.

- **Base**: Alpine Linux 3.23.3
- **Arch**: aarch64 (ARM 64-bit)
- **C library**: musl libc
- **Shell**: BusyBox ash
- **Package manager**: apk

## Usage

```sh
# chroot into the rootfs
sudo chroot /path/to/rootfs-alpine /bin/sh
```
