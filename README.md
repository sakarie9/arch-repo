## Sakari's Pacman Repository

Personal use ArchLinux package repository

### Usage

Add following entry to `/etc/pacman.conf`

```conf
[sakari-aur]
SigLevel = Optional
Server = https://github.com/sakarie9/arch-repo/releases/download/repo
```

And `pacman -Sy` to update repositories

### Related Repos

[PKGBUILDs for packages](https://github.com/sakarie9/PKGBUILDS)
