---
title: Known Issues
---
This section lists the major known issues with Kubernetes vSphere Cloud Provider (VCP). For complete list of issues please check our Github issues(https://github.com/vmware/kubernetes/issues) page. If you notice an issue not listed in Github issues page, please do file a bug on the [Github repo](https://github.com/vmware/kubernetes/issues)

## Release 1.7

* Admin updating the SPBM policy name in vCenter could cause confusions/inconsistencies. [Link](https://github.com/vmware/Kubernetes/issues/156)

* Two or more PVs could show different policy names but with the same policy ID. [Link](https://github.com/vmware/Kubernetes/issues/157)

* Node status becomes NodeReady from NodeNotSchedulable after Failover. [Link](https://github.com/Kubernetes/Kubernetes/issues/45670)

## Release 1.6.5

* Node status becomes NodeReady from NodeNotSchedulable after Failover. [Link]( https://github.com/Kubernetes/Kubernetes/issues/45670)

## Release 1.5.7

* Node status becomes NodeReady from NodeNotSchedulable after Failover. [Link](https://github.com/Kubernetes/Kubernetes/issues/45670)

## vCenter Port other than 443
* For Kubernetes 1.6 and 1.7 releases (except Release v1.7.3 and onwards, Release v1.6.8 and onwards) vCenter Port other than 443 is not supported.

## Validation with Virtual Hardware version (VM version) 13
* Validation of VCP against Container Hosts using Virtual Hardware version 13 is ongoing. [Link](https://github.com/vmware/kubernetes/issues/450)

