# ansible_project


Companion to **[ansible_inventory](https://github.com/playingfield/ansible_inventory)**.

## Prepare
Clone this repo in the same directory as the ansible_inventory.

```bash
git clone https://github.com/playingfield/ansible_inventory.git
git clone https://github.com/playingfield/ansible_project.git
cd ansible_project
git clone
ansible-galaxy install -p ./galaxy -r roles/requirements.yml
./playbook -v --ask-vault-pass
```

The password for the vault is 'password'.

