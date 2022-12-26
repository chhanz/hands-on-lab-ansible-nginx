# hands-on-lab-ansible-nginx
   
## Install Nginx for Amazon Linux 2
```bash
$ ansible-playbook -i inventory install.yml
```
   
## Deploy index.html
```bash
$ ansible-playbook -i inventory site.yml
```
