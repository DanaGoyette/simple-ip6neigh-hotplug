# simple-ip6neigh-hotplug
A simple implementation of ipv6 IP address naming based on OpenWrt hotplug.d scripts

To make the hotplug.d script work, you need to add a line saying `script-arp` (no `=` or anything) to `/etc/dnsmasq.conf`.
