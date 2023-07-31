# Ansible
Create Ansible for Production Environment
# Ansible Playbook for Production Environment

This repository contains an Ansible playbook for managing the production environment.

## Files

- `sshd_config.yml`: Ansible playbook to configure the `sshd_config` on remote servers for improved security.

- `webserver.yml`: Ansible playbook to set up and manage the web server on remote servers.

## Usage

To use the Ansible playbooks, make sure you have Ansible installed on your local machine. If you don't have it installed, follow the installation guide [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### Running the Playbooks

To run the playbooks, use the following command:

```bash
ansible-playbook sshd_config.yml -i inventory_file --user your_ssh_user
```
Replace inventory_file with the path to your inventory file containing the target server(s) information, and your_ssh_user with the appropriate SSH user.

Note: Ensure you have configured your SSH access and have necessary privileges on the remote servers.

Contributing
Contributions are welcome! If you find any issues or improvements, please feel free to submit a pull request.
