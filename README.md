# ANSIBLE_RKE2
Installation
step 1: ssh-copy-id to every node
step 2: add host to inventory.ini
step 3: run the server_install.yaml using: ansible-playbook -i inventory.ini server_install.yaml
step 4: run the worker_install.yaml using: ansible-playbook -i inventory.ini worker_install.yaml