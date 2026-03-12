# Dev Infra

## Pre-requisites

```shell
sudo pacman --sync ansible ansible-runner
```

## Usage

```shell
ansible-galaxy collection install --requirements-file requirements.yml
ansible-playbook archlinux.yml --become-password-file become_pass.txt --vault-id vault_pass.txt --verbose
```
