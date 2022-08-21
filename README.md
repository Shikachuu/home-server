# Home Servers
My home server OS and infrastructural configurations.

## Layout
- Raspberry pi 3b+ as a DNS server
- Zotac Box (Intel(R) Celeron(R) CPU  N3160  @ 1.60GHz + 8 gig ram + 50w adapter) minipc serving as a K8s cluster

## Todo:
- [ ] Install caddy on all the CoreOS instances to proxy promsocket metrics (eg. Zincati) and running podman containers
- [ ] Migrate the k8s cluster to c3os
- [ ] Add CI pipeline to automatically produce ignition files
- [ ] Add auto update for k3s
