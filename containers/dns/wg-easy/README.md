## Requirements

- yq
- podman ^4.4

## Install

- replace the password in the secret.yaml with yq `yq e -i '.data.password = "my-secret-password"' wg-easy-deployment.yaml`
- copy the `wg-easy.kube` file to `/etc/containers/systemd/wg-easy.kube`
- copy the `wg-easy-deployment.yaml` file to `/opt/containers/wg-easy-deployment.yaml`
- run `sudo systemctl daemon-reload`
- enable the wg-easy service `sudo systemctl enable --now wg-easy`