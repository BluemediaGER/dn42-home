---
title: bluemedia.dn42
draft: false
---

#### An experiment in global routing.

----------------
<div align="left">

### About
bluemedia.dn42 (AS4242423343) is my personal experimental network within <a href="https://dn42.dev" target="_blank">DN42</a>. The network is well connected with others and is currently mainly present in Germany.

### Topology

The bluemedia.dn42 network currently consists of two public and one internal node. All nodes within the network form a full mesh using wireguard tunnels. iBGP is used as the interior gateway protocol. Services such as DNS and websites are hosted centrally behind the internal node.

### Techstack

The following tools and programs are used to run the bluemedia.dn42 network and core services:
- <a href="https://www.debian.org/" target="_blank">Debian 10</a> - OS used on all host systems
- <a href="https://bird.network.cz/" target="_blank">bird2</a> - Routing daemon used on all nodes
- <a href="https://www.wireguard.com/" target="_blank">WireGuard</a> - VPN protocol used to connect all nodes
- <a href="https://www.isc.org/bind/" target="_blank">BIND 9</a> - Authoritative DNS server for forward and reverse zones
- <a href="https://nlnetlabs.nl/projects/unbound/" target="_blank">Unbound</a> - Recursive DNS resolver

</div>