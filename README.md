# Ansible Mac Setup Playbook

## Install third party roles
```bash
ansible-galaxy install -r requirements.yml
```

### Run playbook using this command for testing purposes
Remove the --check flag whenever want to install for real.

```bash
ansible-playbook -i inventory.yml setup.yml --check
```
