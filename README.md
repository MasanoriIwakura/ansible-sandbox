# ansible-sandbox

Ansible 学習用リポジトリ

## 環境

- macOS Catalina
- Python 3.7.4
- Ansible 2.9.6
- Vagrant 2.2.6

## Setup

```sh
# Download
git clone https://github.com/MasanoriIwakura/ansible-sandbox.git
cd ansible-sandbox

# Vagrant setup
vagrant up
vagrant ssh-config --host ansible-sandbox >> ~/.ssh/config

# Execute PlayBook
ansible-playbook -i inventory playbook.yml
```
