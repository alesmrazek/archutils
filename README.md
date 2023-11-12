# archutils

This repository provides my personal tools for installing Arch Linux.

**Use at your own risk.**

1. Boot live environment of the Arch Linux installation image.
    - https://wiki.archlinux.org/title/installation_guide#Acquire_an_installation_image
2. Connect to the Internet.
    - https://wiki.archlinux.org/title/installation_guide#Connect_to_the_internet
3. Get/download the repository with `wget` or with any other utility (`curl`, `git`).
```bash
$ wget  https://github.com/mrazekales/archutils/tarball/main -O - | tar xz
```

### archinstall

Arch Linux installation script - partitioning, formating and base system installation/configuration.

Run `archinstall` stcript.
```bash
$ cd archutils
$ sh archinstall 
```

## Reference
- https://wiki.archlinux.org/index.php/installation_guide
