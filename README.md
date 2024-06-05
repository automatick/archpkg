# Arch linux package manager
Thats support appimage, aur, flatpak
To install it enter this commands

```bash
git clone https://github.com/automatick/archpkg.git
cd archpkg
sh archpkginstall
```
It's installs all deperencies and move archpkg to /bin.
Than you check of instalation success

```bash
-> archpkg
Usage: archpkg <command> [options]
              install <package> - installs package
                  install options:
                    --appimage - installs appimage
                    --aur - installs aur package
                    --pacman - installs pacman package
                    --flatpak - installs flatpak package
               pm add options:
                    --pacmaninstall - installs pacman
                    --aurinstall - installs aur
                    --flatpakinstall - installs flatpak
              remove <package> - removes package
                  remove options:
                    --pacrm - removes pacman package
                    --aurrm - removes aur package
                    --flatpakrm - removes flatpak package
            default: aur install
```
If instalation was success you can use command to install/remove packages.
Samples:

Install AppImage package:
```bash
archpkg install --appimage Test.AppImage
```
Install aur package:
```bash
archpkg install --aur vim
```
or
```bash
archpkg install vim
```
Remove appimage package:
```bash
archpkg remove --apprm Test
```
Remove aur package:
```bash
archpkg remove --aurrm vim
```
