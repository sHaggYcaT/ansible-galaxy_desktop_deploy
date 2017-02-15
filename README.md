In first step, please run command:

ANSIBLE_CONFIG=ansible.cfg  ansible-galaxy install -r requirements.yml

This command deploy all required roles from repos.

In second step, please run playbook using command:

ANSIBLE_CONFIG=ansible.cfg ansible-playbook -i desktop, -c local desktop.yml

## TODO

####1 write all features

####2 fix bugs

