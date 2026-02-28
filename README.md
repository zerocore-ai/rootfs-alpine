# rootfs-alpine

Alpine Linux v3.23 root filesystems.

- **Base**: Alpine Linux 3.23.3
- **C library**: musl libc
- **Shell**: BusyBox ash
- **Package manager**: apk

## Architectures

| Directory | Arch |
|-----------|------|
| `aarch64/` | ARM 64-bit |
| `x86_64/` | x86 64-bit |

## Usage

```sh
# chroot into a specific arch rootfs
sudo chroot /path/to/rootfs-alpine/aarch64 /bin/sh
sudo chroot /path/to/rootfs-alpine/x86_64 /bin/sh
```
