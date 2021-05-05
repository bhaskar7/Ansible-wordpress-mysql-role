# Ansible-wordpress-mysql-role

Enter your Access key & secret key in aws_ec2.yml file
Go to the ansible.cfg file and upadte current path in the ansibel role .
Create your own valut using #ansible-vault create vault.yml & enter your secret key and access key.
Make sure your aws key should be present in your current folder & update the key name in the ansible.cfg file
Run ec2-launch.yml file first i.e ansible-playbook --ask-vault-pass ec2-launch.yml
Then Run ansible main.yml cmd.

