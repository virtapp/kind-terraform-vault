# vault-consul-demo

This is a demo for demonstrate secret management via vault with consul

## Prerequisites

- [terraform](https://www.terraform.io/downloads.html)
- [docker](https://www.docker.com/products/docker-desktop)
- [skaffold](https://skaffold.dev/docs/install/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [kustomize](https://kubectl.docs.kubernetes.io/installation/kustomize)
- [kind](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
- [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Usage

initialize terraform module

```bash
$ terraform init
```

run terraform to create cluster with vault and consul

```bash
$ terraform apply -auto-approve
```

