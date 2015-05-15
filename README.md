Ansible playbook used to install OpenVAS 8.0 in Ubuntu

Instructions:

Create a file called hosts containing the ip address of the host where you want OpenVAS installed.

Runt the playbook:

    ansible-playbook playbooks/setup_openvas.yml -i hosts

You may then use ssh + forwarded port 80 to access the service.