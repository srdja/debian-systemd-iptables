#### Unofficial Debian package of systemd iptables service

Based on an Arch Linux [package](https://www.archlinux.org/packages/core/x86_64/iptables/)

You can download the `.deb` package from  [here](https://github.com/srdja/debian-systemd-iptables/releases/download/1.0.0/systemd-iptables_1.1-0.deb) or you can package it manually.

### Building the package

run `dpkg-deb --build systemd-iptables1.1-0` to build a `.deb` package

### Installing

`sudo dpkg -i systemd-iptables_1.1-0.deb`

### Uninstalling

`sudo dpkg -r systemd-iptables`



NOTE: Iptables rules should be saved to `/etc/iptables/iptables.rules` or `/etc/iptables/ip6tables.rules`
