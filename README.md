# Steps

## Install Anisble on ubuntu

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible=5.10.0-1ppa~focal
```

## Install ansible roles and collections from galaxy

```ansible-galaxy install -r requirements.yml```


### Run playbook

```ansible-playbook provision.yml```
