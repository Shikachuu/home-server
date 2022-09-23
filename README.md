# Home Servers
My home server OS and infrastructural configurations.

## Layout

| Device               | Role                                         | OS                                                                  | Hardware                                                             |
| -------------------- | -------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Raspberry Pi 3b+     | DNS server                                   | [kairos](https://kairos.io)                                         | -                                                                    |
| Raspberry Pi 4b      | K8s Monitoring server (Prometheus + Loki)    | [kairos](https://kairos.io)                                         | -                                                                    |
| Zotac Box            | Kubernetes application server + main ingress | [kairos](https://kairos.io)                                         | Intel Celeron N3160 @ 1.60GHz + 8 gig ram + 50w adapter              |
| Project Data Bank    | NAS                                          | [TrueNAS Scale](https://www.truenas.com/download-truenas-scale/)    | Intel i5 7500 + 8 gig ram + 400w FSP gold PSU + 2x 480 GB Kioxia SSD |
| TP-Link Archer C6 v3 | Router + DHCP                                | [OpenWRT SNAPSHOT](https://openwrt.org/toh/tp-link/archer_c6_v3)    | MediaTek MT7621                                                      |

This repository contains all the `kairos` config that required to boot the os with the given services on the listed devices.
