## *playbooks*
>This project is only intended to share some simple playbooks (yaml scripts) for ansible 2.2 under debian.

>For example you can install apache2 with default configuration using "webserver.yaml" playbook:
if your inventory file is in default location (/etc/ansible/hosts) simply type:

####install apache2:
```
$ ansible-playbook webserver.yaml
```
####stop apache2:
```
$ ansible-playbook webserver_stop.yaml
```
####restart:
````
$ ansible-playbook webserver_start.yaml
````

####To install simply run:
````
$ git clone https://github.com/mixer3d/playbooks.git
````
read more:
- [ansible](https://docs.ansible.com/ansible/index.html)
- [debian](https://www.debian.org/)

Happy Hacking :)

*mixer3d*


