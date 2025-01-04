# Archlinux

## Desktop
- [Gnome](/gnome.md)
- gnome-extra
- gnome-firmware
- gnome-themes-extra

## App

### System
- Yay [github](https://github.com/Jguer/yay?tab=readme-ov-file#installation)
- power-profiles-daemon (option for gnome-control-center)
- BpyTOP
- nvtop
- fastfetch
- plymouth [systemd-boot](/plymouth-systemd-boot.md)
- [ssh](/ssh.md) (private key)

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
