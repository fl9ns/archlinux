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

### Mirror (reflector)
```sudo reflector --save /etc/pacman.d/mirrorlist --sort score --verbose --country France --fastest 10 --protocol https --ipv4```

### Fonts
```pacman -S noto-fonts-{cjk,emoji,extra} adobe-source-han-sans-otc-fonts```

### Other
- [Firefox](/firefox.md)
- Code-oss
- Chatterino
- MPV
- [protonup-qt](https://aur.archlinux.org/packages/protonup-qt)

## Wifi
help : [wiki](https://wiki.archlinux.org/title/Iwd)

- ```iwctl```
- ```station <wlan0> connect <SSID>```
- ```station <wlan0> connect-hidden <SSID>```

## Help

```sudo pacman -Syyu --overwrite "*"```
