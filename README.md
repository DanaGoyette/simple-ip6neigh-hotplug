# simple-ip6neigh-hotplug
A simple implementation of ipv6 IP address naming based on OpenWrt hotplug.d scripts

To make the hotplug.d script work, you need to add a line to `/etc/dnsmasq.conf`:
```
script-arp
```
(no `=` or anything)

This is just an experiment.  I've noticed that old records will linger
rather than getting cleaned up, perhaps because of dnsmasq restarting.
