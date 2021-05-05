# Ansible-wordpress-mysql-role

1. Enter your Access key & secret key in aws_ec2.yml file
2. Go to the ansible.cfg file and upadte current path in the ansibel role .
3. Create your own valut using **ansible-vault create vault.yml** & enter your secret key and access key.
4. Make sure your aws key should be present in your current folder & update the key name in the ansible.cfg file
5. Run ec2-launch.yml file first i.e **ansible-playbook --ask-vault-pass ec2-launch.yml**
6. Then Run **ansible-playbook main.yml** cmd.

