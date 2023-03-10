# Day7

## Ansible Tower opensource Installation (AWX)
```
https://github.com/ansible/awx-operator
```

## Installing Ansible Tower in Ubuntu
```
https://cloudinfrastructureservices.co.uk/how-to-install-ansible-awx-tower-on-ubuntu-20-04-server/
```

## What is Ansible Role?
- role is a reusable code
- roles can't be executed independently
- roles can be invoked via Playbooks
- roles are similar to Dynamic Link Library (DLL), just like DLL functions(code) are invoked from applications, roles can be invoked via Playbook
- roles follow a specific directory structure
- roles directory structure can be created using ansible-galaxy tool
- there is also a galaxy web portal that has many reusable opensource roles that you install using ansible-galaxy tool

## Ansible Galaxy portal
```
https://galaxy.ansible.com/home
```

## ⛹️‍♂️ Lab - Using custom ansible role in Playbook
```
cd ~/ansible-jan-2023
git pull

cd Day7/custom-ansible-role
ansible-playbook playbook.yml
```
