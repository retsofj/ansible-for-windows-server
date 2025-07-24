# ansible-for-windows-server
The purpose of this repo is to help provide example Ansible playbooks/roles managing Windows Server for administrators/engineers. Be sure to also check out the examples [devops-school](https://gist.github.com/devops-school/52c8de8924555f91c50e3a016556060f) has published.

# Examples
- Server type:
  - Volume Activation server
- Common task:
  - Create local user

# Notes:
- You may need the following modules:
  - [ansible.windows](https://docs.ansible.com/ansible/latest/collections/ansible/windows/)
  - [ansible.posix](https://docs.ansible.com/ansible/latest/collections/ansible/posix/)
  - [community.general](https://docs.ansible.com/ansible/latest/collections/community/general/)
  - [community.windows](https://docs.ansible.com/ansible/latest/collections/community/windows/)
- Modules can be downloaded in the following fashion: `ansible-galaxy collection install COLLECTION.NAME`

# Resources
- [Configuring your server to work with Ansible via SSH](https://docs.ansible.com/ansible/latest/os_guide/windows_ssh.html)
- [Windows usage](https://docs.ansible.com/ansible/latest/os_guide/windows_usage.html)
