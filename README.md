# Ansible-scripts

ansible-playbook -i myhosts.ini check_using_vault.yml --ask-vault-pass

vi myhosts.ini

[jboss_servers]
172.31.23.22
172.31.30.167

[local]
localhost ansible_connection=local



ansible-vault encrypt secrets.yml

ansible-vault decrypt secrets.yml

sudo ansible-vault edit secrets.yml


vi secret.yml-----

---
ansible_user: suraj
ansible_ssh_pass: ssp141998
