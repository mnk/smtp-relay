SMTP Relay
==========

This Ansible playbook configures an SMTP relay running on Linode to forward emails from one or more personal domains to
ordinary GMail accounts.

To setup the relay run:

        ansible-playbook -i ../inventory/hosts.yml install-host.yaml