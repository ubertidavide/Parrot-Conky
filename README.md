# Parrot Conky
Conky is a system monitor for Parrot Security Os, this is a fork of the official parrot-conky created by Lorenzo "Palinuro" Faletra, fixed for the latest Parrot Os Version(3.2).

## Documentation
* [Conky GitHub Page](https://github.com/brndnmtthws/conky)
* [Configure](https://github.com/brndnmtthws/conky/wiki/Configuration-Settings)
* [User Configs](https://github.com/brndnmtthws/conky/wiki/User-Configs)

## Set Cpu Numbers
By default cpu number is four, for change it go to `/etc/conky/rings.lua` and change only the variable `cpu_number = 4`.

## Install
Copy all the file from the folder
```
sudo cp ./etc/conky/conky.conf /etc/conky/conky.conf
sudo cp ./etc/conky/parrot.png /etc/conky/parrot.png
sudo cp ./etc/conky/rings.lua /etc/conky/rings.lua
sudo cp ./usr/share/applications/conky-start.desktop /usr/share/applications/conky-start.desktop
sudo cp ./usr/share/truetype/future/future.ttf /usr/share/truetype/future/future.ttf
```
Start conky
```
conky
```
Conky Autostart
## Changelog
* [13/12/2016] It work with the latest version of Parrot(3.2).
* [13/12/2016] Simplified the setting of the processors number.
* [14/12/2016] Fixed the problem with the distro info.
