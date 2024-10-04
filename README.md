# Ansible
Ansible is openSource
This is 100% Agentless
This works both on push and pull mechanism

Ansible can be operated in 2 ways :
1) Manual way    ( No Code Approach and it's 100% not recommended )
2) Automated way ( YAML : Playbooks : 100% recommended approach )


Install Ansible :
curl https://gitlab.com/thecloudcareers/opensource/-/raw/master/lab-tools/ansible/install.sh | sudo bash

Ansible is about all modules


ansible all -i inv -e ansible_user=centos -e ansible_password=DevOps321 -m shell -a uptime

$ gp;ansible-playbook -i inv -e ansible_user=centos -e ansible_password=DevOps321 -e URL=Ci.google.com 004-shell.yaml

If you go with tihs approach, you can run or execute only one command/action at a time

Automated with Ansible is called playbooks and playbooks can be written by YAML(Presentation langauge)

```$ ansible-playbook -i inv -e ansible_user=centos -e ansible_password=DevOps321 pbName.yaml```
