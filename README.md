# ansible-for-windows-server
The purpose of this repo is to help provide example Ansible playbooks/roles managing Windows Server for administrators/engineers.

# Examples
- Server type:
  - Volume Activation server
- Common task:
  - Create local user

# Notes:
- You may need the following modules:
  - ansible.windows
  - ansible.posix
  - community.general
  - community.windows
- Modules can be downloaded in the following fashion: `ansible-galaxy collection install COLLECTION.NAME`

# Resources
- [Configuring your server to work with Ansible via SSH](https://docs.ansible.com/ansible/latest/os_guide/windows_ssh.html)
- [Windows usage](https://docs.ansible.com/ansible/latest/os_guide/windows_usage.html)
