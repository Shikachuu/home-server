## Requirements

- podman ^4.4
- systemd

## Install

- copy the `blocky.kube` file to `/etc/containers/systemd/blocky.kube`
- copy the `blocky-deployment.yaml` file to `/opt/containers/blocky-deployment.yaml`
- run `sudo systemctl daemon-reload`
- enable the blocky service `sudo systemctl enable --now blocky`