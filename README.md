# playbooks
This project is only intended to share some simple playbooks (yaml scripts) for ansible 2.2 under debian.

For example you can install apache2 with default configuration using "webserver.yaml" playbook:
if your inventory file is in default location (/etc/ansible/hosts) simply type:

to install apache2:
$ansible-playbook webserver.yaml

to stop apache2:
$ansible-playbook webserver_stop.yaml

to restart:
$ansible-playbook webserver_start.yaml

I'm working on some implementation so I thought that this can be usefull also for others... ;)

To install simply run:
$git clone https://github.com/mixer3d/playbooks.git

To read about ansible:
https://docs.ansible.com/ansible/index.html

To read about debian:
https://www.debian.org/

Happy Hacking :)
mixer3d


