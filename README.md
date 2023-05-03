# arch-packages (source branch)

Personal package repository

To use it, add

```ini
[usa-reddragon]
Server = https://raw.githubusercontent.com/USA-RedDragon/arch-pkgbuilds/bins/$arch
```

to your `/etc/pacman.conf` and install the `usa-reddragon-keyring` package:

```bash
wget https://github.com/USA-RedDragon/arch-packages/raw/bins/x86_64/usa-reddragon-keyring-20230501-3-any.pkg.tar.zst
sudo pacman -U usa-reddragon-keyring-20230501-3-any.pkg.tar.zst
```
