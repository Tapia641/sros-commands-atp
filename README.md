To install it, use: 

``
pip3 install ansible
``
``
ansible-galaxy collection install community.network.
``


Generate a rol:

``
ansible-galaxy init role-name
``


To use it: The scope is basic testing of WBX-210 acting as “leaf-switch” in Nuage Network Architecture.

``
ansible-playbook main.yml -i inventory/inventory.ini
``# ansible-common
