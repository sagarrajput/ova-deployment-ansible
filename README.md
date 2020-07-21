# ova-deployment-ansible

Automate vSphere OVA Appliance Deployments Using Ansible playbook, Ansible provides the vmware_deploy_ovf module that can be used to deploy OVA/OVF appliances.

## Pre-requisites

You will need to have the following packages installed on your Machine:

1. ansible>=2.8.0
2. pyvmomi>=6.7.1.2018.12

## How to run use this

1. Edit deploy_ova.yml playbook to add your VMware vSphere clinet details and path of your OVA file.
2. To deploy the appliance, run the playbook by invoking the ansible-playbook command.
   ansible-playbook deploy_ova.yml
