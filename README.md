# ansible4azure
Example playbooks for Azure

The vaulted file files/account contains 2 populated vars: account_username & account_password

These will be used by the playbooks to give a VM on a local admin account for Ansible/Tower to use for automation.

If you want to use this construct yourself, you need to replace this file with your own and thus with your own account_username/account_password and your own vault password. If not, provide your own clear text values to the playbook.
