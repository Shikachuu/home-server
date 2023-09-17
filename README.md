# Home Servers

My home server OS and infrastructural configurations.

## Layout

| Device | Role | OS | Hardware |
|--------|------|----|----------|
| Raspberry Pi 4b | [DNS server](os-config/dns.yaml) | [fedora server](https://docs.fedoraproject.org/en-US/fedora-server/server-on-sbc/) | - |
| Zotac Box       | [Kubernetes application server + main ingress](os-config/picloud.yaml) | empty | Intel Celeron N3160 @ 1.60GHz + 8 gig ram + 50w adapter |
| TP-Link Archer C6 v3 | Router + DHCP | [OpenWRT SNAPSHOT](https://openwrt.org/toh/tp-link/archer_c6_v3) | MediaTek MT7621 |
| HP ProLiant MicroServer Gen10 | NAS + Storage | [TrueNAS Core](https://www.truenas.com/truenas-core/) | AMD Opteron X3216, 8GB DDR4 2400MHz Unbuffered ECC, 2xWD Red 2TB |

This repository contains all the os config that required to boot the os with the given services on the listed
devices.
