# ansible-role-nexus

repository: `git@gitlab.com:lamtech-tooling/ansible-roles/ansible-role-nexus.git`

**Description:**
The aim of this project to set up Nexus to store artifacts.

**Prerequisites:**
- Ansible core version: ~>2.1.3
- Python3: ~>3.1.2

**Installation:**
1. Install Python
2. Install Ansible core
3. Install Ansible Modules

Configurations - Define the following
1. aws.ec2.yml
2. requirements.yml
3. site.yml
4. roles

Commands
1. Install ansible role. Run the following command: `ansible-galaxy install -r requirements.yml --roles-path roles`
2. Deploy the Nexus Application. Run the following command: `ansible-playbook -i aws_ec2.yaml site.yml -b -u ec2-user --private-key=~/.ssh/file.pem`





