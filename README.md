# CMPE272-Ansible-Webserver-VMs Assignment 1:

This project contains two Ansible playbooks for automating the deployment and un-deploying of web servers on two Virtual Machines (VM1 and VM2). The playbooks configure the web server to serve a custom "Hello World from SJSU- X" message based on the VM number it is deployed on and allow easy un-deployment when needed. 

## Playbooks
- webserver-playbook.yml: This playbook installs and configures the Apache web server on both VMs, sets it up to listen on port 8080, and deploys a custom HTML page that displays "Hello World from SJSU-1" or "Hello World from SJSU-2" based on the VM.
- un-deploy-playbook.yml: This playbook stops and removes the Apache web server from both VMs, cleaning up the configuration and the custom HTML page.

## Other Files
- inventory.ini: Defines the two VMs (VM1 and VM2) that Ansible will manage. This file contains the IP addresses of the VMs along with the username created while creating the VM.

Please refer to the document added on Canvas for screenshots of the output. 
