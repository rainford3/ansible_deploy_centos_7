# ansible_deploy_cemtos_7

This is a playbook to configure a newly deployed vm from a preconfigured template. The playbook currently performs the following tasks:
- creates a new vm in vcenter using an existing template
- configures hostname
- configures the network (firewalls)
- configures ssh (hardening and ssh key auth)
- updates all software packages and install a common tool set
- configures authentication against active directory using realm
