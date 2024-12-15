# Archlinux

## Desktop
- [Gnome](/gnome.md) (4 12 14 23 24 25 48 58) (6 15 17 38)
- gnome-extra (7 38)

## App

### System
- Yay [github](https://github.com/Jguer/yay?tab=readme-ov-file#installation)
- power-profiles-daemon (option for gnome-control-center)
- BpyTOP
- nvtop
- fastfetch
- plymouth [systemd-boot](/plymouth-systemd-boot.md)
- ssh [ssh-agent](/ssh.md)

### Fonts
```pacman -S noto-fonts-{cjk,emoji,extra} adobe-source-han-sans-otc-fonts```

### Other
- [Firefox](/firefox.md)
- Code-oss
- Chatterino
- MPV

## Wifi
help : [wiki](https://wiki.archlinux.org/title/Iwd)

- ```iwctl```
- ```station <wlan0> connect <SSID>```
- ```station <wlan0> connect-hidden <SSID>```

## Help

```sudo pacman -Syyu --overwrite "*"```
