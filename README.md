# Proxmox cluster repository

Install and configure Proxmox cluster

# Dependencies

- ansible >= 2.2.0
- servers with installed Proxmox on Debian Stretch (based on image provided by Hetzner)
- nodes with 2 network interfaces
- prepared disk partitions which will be formatted

# Variables

Please check [group_vars/all/vars](group_vars/all/vars)

# Usage

```sh
ansible-galaxy install -f -r roles/requirements.yml
ansible-playbook playbooks/site.yml
```
