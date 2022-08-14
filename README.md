# EasyEffects SystemD
Service unit file for easy effects

## Installation
```shell
$ git clone https://github.com/rizzzigit/easyeffects-systemd
$ cd easyeffects-systemd
$ makepkg
# pacman -U easyeffects-systemd-1.0-1-any.pkg.tar.zst
```


## Usage
To start the service on user login:
```shell
$ systemd --user enable easyeffects
```

To start or stop the service:
```
$ systemd --user start easyeffects
$ systemd --user stop easyeffects
```
