# Ansible Playbook for Arch Linux

General configuration of my Arch Linux installation automated using Ansible.

## Dependencies

- `ansible-aur-git` - *Ansible module to install AUR packages*
- `yay` - *AUR helper*

## Running

```
ansible-playbook playbook.yml -i inventory/inventory.yml --ask-become-pass
```
