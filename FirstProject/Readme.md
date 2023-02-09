# Ansible command line

ansible -u installer -i hosts -m ping all

ansible -u installer -i hosts -m ping group1

ansible -u installer -i hosts -m ping "group*"