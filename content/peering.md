---
title: Peering
draft: false
---

This page will provide you some information if you want to peer with the bluemedia.dn42 network. New peers are always welcome.

*However, please make sure you have read the information below before sending a peering request.*

### Peering Requests

Please email [dn42@bluemedia.dev](mailto:dn42@bluemedia.dev) for new peering requests or if you want to change existing peerings.

### Requirements

If you want to peer with me, you must meet the following requirements:
 - You are able to connect via wireguard.
 - Your network supports IPv6.
 - You implement ROA checks against the DN42 registry.
 - Your contact information in the registry is to be up to date. I expect you to respond to contact requests within a reasonable amount of time.

### Required Information

At a minimum, I need the following information from you to configure a peering session:
 - Name of the bluemedia.dn42 node you want to peer with - see [IPAM](/ipam/) for an up to date list
   - Peering in multiple locations is possible
 - Your ASN
 - Public address / domain name of your host
 - Tunnel and BGP parameters, e.g.
   - Port number for wireguard
   - Public key for wireguard
   - IP addresses of your tunnel endpoint
     - This will be a single IPv4 /32 and Link-Local IPv6 address in most cases

All peering sessions will be configured as full transit sessions.

### Additional information

#### Route Filtering

My network applies strict Route Origin Authorization (ROA) filtering on all imported and exported routes. Any advertised route that does not have a corresponding route{,6} object in the DN42 registry will be dropped.

#### Reachability Testing an Debugging

I have a <a href="/lg">looking glass</a> that you can use to check your routing configuration.  
Looking glasses are important if you want to understand how your routes are distributed in the DN42 network. So it's best to learn how to use them right away. 
