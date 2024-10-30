# Ansible Mac Setup Playbook

## Install third party roles
```bash
ansible-galaxy install -r requirements.yml --ignore-certs
```

### Run playbook using this command for testing purposes
Remove the --check flag whenever want to install for real.

```bash
ansible-playbook -i inventory.yml main.yml --check
```


Notes: Could not get Ansible Galaxy role: geerlingguy.mac.dock to work from ansible galaxy.
Heavily influenced and borrowed from https://github.com/geerlingguy/ansible-collection-mac