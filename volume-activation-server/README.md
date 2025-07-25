This role is based off of [Microsoft's documentation](https://learn.microsoft.com/en-us/windows-server/get-started/kms-create-host) for creating a KMS activation host. It will do the following steps:
1. Install the Volume Activation Services role with management tools
2. Reboot the server, if necessary
3. Configure Windows Firewall to allow KMS to receive network traffic

You will still need to run the wizard to configure the host, as well as any further steps in the Microsoft documentation.

I have also included a playbook that does all of the same steps if you are more comfortable with that process
