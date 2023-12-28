# Ansible Learning Repository
This repository serves as a learning ground for exploring Ansible's capabilities. It contains customized roles derived from various sources, primarily obtained from Ansible Galaxy. The roles sourced from Ansible Galaxy were modified and tailored further to deepen understanding and proficiency in working with Ansible.

## Roles Used and Customized:

### self_custom_apache

This role, originally sourced from the [Geerlingguy Apache role on Ansible Galaxy](https://galaxy.ansible.com/ui/standalone/roles/geerlingguy/apache/), has undergone specific customizations within this repository:

- **Allow Using Multiple Virtual Hosts with ServerName:** The role has been modified to enable the usage of multiple virtual host configurations utilizing the `ServerName` directive. This enhancement allows for better organization and management of multiple websites on RedHat-based systems.

- **Removal of Default Virtual Host Configuration Files:** The customized role includes logic to remove all default virtual host configuration files. This action helps maintain a clean and organized Apache configuration directory by removing unnecessary default configurations.

- **Additional Virtual Host Configuration for Disabling IP Access:** An extra virtual host configuration has been added to restrict access to the web server via its IP address. This additional configuration strengthens security by denying direct access through the IP while allowing access only through specified domain names.

These customizations enhance the functionality and security of the Apache web server in RedHat environments, offering improved management of virtual hosts and strengthened access control.
