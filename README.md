In this project we are going to send an e-mail directly through Gmail server using mail module after configuring our own local system using AnsibleVault Feature of Ansible.

Requirements:
* Ansible installed and configured on our Controller/Manager node.
* Account on Gmail.
* Gmail Less Secure app : Disabled (https://myaccount.google.com/lesssecureapps)

Information:
* Google-mail/Gmail server address(Host address) : smtp.google.com
* Port no: 465(unsecure) , 587(secure)

Files:
* mail.yml: playbook for performing task
* var.yml: vault file for storing my playbook-variables 
