In first step, please run command:

ANSIBLE_CONFIG=ansible.cfg  ansible-galaxy install -r requirements-elementary.yml

This command deploy all required roles from repos.

In second step, please run playbook using command:

ANSIBLE_CONFIG=ansible.cfg ansible-playbook -i desktop, -c local elementary-desktop.yml

If you want to install Fedora 25 LXQt or KDE, please run commands:
ANSIBLE_CONFIG=ansible.cfg ansible-galaxy install -r requirements-fedora.yml

ANSIBLE_CONFIG=ansible.cfg ansible-playbook -i desktop, -c local desktop-fedora-lxqt.yml

ANSIBLE_CONFIG=ansible.cfg ansible-playbook -i desktop, -c local desktop-fedora-kde.yml

## TODO

####1 write all features

####2 fix bugs

