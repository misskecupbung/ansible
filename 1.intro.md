## Introduction
Ansible:
* Simple
* Powerfull
* Agentless

Architecture:
* Control nodes
* Managed hosts

Components:
* Inventory: List that contain managed hosts
* Modules: small piece of code
* Plugins: code that you can add to ansible to extend it and adapt to new uses and platform
* API
* Ansible Playbooks
* Hosts

Ansible ways:
* Complexity kills productivity
* Optimize for readibility
* think declaratively

Use cases:
* Configuration management
* Application deployment
* Provisioning
* CI
* Security Delivery
* Orchestration


## Installation Guide


### Centos 7

```
yum update && yum upgrade -y
yum install dnf -y
dnf update -y
dnf install python3 -y
dnf install python3-pip -y
pip3 install ansible –user
```
### check version
```
ansible --version
ansible -m setup localhost | grep ansible_python_version
```
