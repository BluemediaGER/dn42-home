---
title: IPAM
draft: false
---

This page contains information about the prefixes announced by bluemedia.dn42 and their purpose.

bluemedia.dn42 announces the folloing prefixes:
- fd75:eca7:b62a::/48
- 172.22.167.80/28

### bluemedia.dn42 Services

{{< bootstrap-table "table table-striped table-bordered" >}}
|DNS|IPv4|IPv6|Comment|
|---|----|----|-------|
|ns1.bluemedia.dn42|172.22.167.90|fd75:eca7:b62a:40::53|Authoritative name server|
|resolver.bluemedia.dn42|172.22.167.91|fd75:eca7:b62a:40::54|Recursive DNS resolver|
|web1.bluemedia.dn42|172.22.167.92|fd75:eca7:b62a:40::80|Web server|
{{< /bootstrap-table >}}

### bluemedia.dn42 Nodes (DN42 addressing)

{{< bootstrap-table "table table-striped table-bordered" >}}
|DNS|IPv4|IPv6|Comment|
|---|----|----|-------|
|de-fsn01.bluemedia.dn42|172.22.167.81|fd75:eca7:b62a:10::1|Hetzner Online, Falkenstein, Germany|
|de-fra01.bluemedia.dn42|172.22.167.82|fd75:eca7:b62a:20::1|Oracle Cloud, Frankfurt am Main, Germany|
|de-kkb01.bluemedia.dn42|172.22.167.89|fd75:eca7:b62a:40::1|Internal node|
{{< /bootstrap-table >}}

### bluemedia.dn42 Nodes (Internet addressing)

{{< bootstrap-table "table table-striped table-bordered" >}}
|DNS|IPv4|IPv6|Comment|
|---|----|----|-------|
|de-fsn01.dn42.bluemedia.dev|157.90.153.123|2a01:4f8:1c17:6d31::1|Hetzner Online, Falkenstein, Germany|
|de-fra01.dn42.bluemedia.dev|152.70.171.183|2603:c020:8002:8100:1e75:2674:eb2e:108a|Oracle Cloud, Frankfurt am Main, Germany|
|de-kkb01.dn42.bluemedia.dev|(dynamic)|(dynamic)|Internal node|
{{< /bootstrap-table >}}

