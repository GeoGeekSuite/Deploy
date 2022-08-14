# Deploy
Ansible Script to deploy the environment

Save inventory_sample.yaml as inventory.yaml and fill in connection details.

Clone additional roles from git
'''
ansible-playbook ./helper/get_roles.yaml
'''

Run the main playbook:
'''
ansible-playbook main.yaml --ask-become-pass
'''
