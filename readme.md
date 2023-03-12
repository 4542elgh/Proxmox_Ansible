Python should be pre-installed in Debian/Ubuntu system
```bash
curl -LO https://github.com/4542elgh/Proxmox_Ansible/archive/refs/heads/main.zip
unzip main.zip
cd Proxmox_Ansible-main

ansible-playbook -i inventory.yaml playbook.yaml --ask-vault-pass -v
```
