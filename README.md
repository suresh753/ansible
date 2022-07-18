# Steps

## Install Anisble on ubuntu

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible=5.10.0-1ppa~focal
```

## Install ansible galaxy roles

```ansible-galaxy role install -r requirements.yml```

## Install ansible galaxy colletions

```ansible-galaxy collection install -r requirements.yml```

### Run playbook

```ansible-playbook provision.yml```
