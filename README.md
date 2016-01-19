#### Unofficial Debian package of systemd iptables service

Based on an Arch Linux [package](https://www.archlinux.org/packages/core/x86_64/iptables/)


### Building the package

`dpkg-deb --build systemd-iptables_1.0-0`

### Installing

`sudo dpkg -i systemd-iptables_1.0-0.deb`

### Uninstalling

`sudo dpkg -r systemd-iptables`



Iptables rules should be saved to `/etc/iptables/iptables.rules` or `/etc/iptables/ip6tables.rules`
