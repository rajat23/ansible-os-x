# Ansible-os-x

Install MySQL on OS X using the ansible playbook
============
Prerequisites:
========================================================
You should have ansible installed on machine where you would like to play this ansible playbook

- On Mac OS-X ,install ansible using ```` brew install ansible ````
- You should have RSA Key generated on your machine. If not follow this link ````https://help.github.com/articles/generating-ssh-keys/````

To Run playbook
===============

- First clone the repositoy using ```` git clone https://github.com/rajat23/ansible-os-x.git ````
- Go to ````/ansible-os-x/ansible````
- Now run the playbook from this directory using command ````ansible-playbook playbook/mysql.yml -i host.inventory -vvvv````

Issues
======
- If you do face issue please raise a issue , I would be happy to help

Contribution
============
- If you feel to contribute to this project(e.g some more playbooks).Please raise a pull request


