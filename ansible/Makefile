ping:
	ansible -i inventory.yml -m ping all

galaxy:
	ansible-galaxy collection install -r collections/requirements.yml

site:
	ansible-playbook -i inventory.yml site.yml -v
