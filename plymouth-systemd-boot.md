# Plymouth

```
# pacman -S plymouth
```

# .conf

```
# vim etc/mkinitcpio.conf

HOOKS=(base udev plymouth ...)
```

```
# vim boot/loader/entries/*.conf

options ... quiet splash
```

source : [reddit](https://www.reddit.com/r/archlinux/comments/1c5zt8n/install_enable_plymouth_on_arch_linux_systemdboot/)
