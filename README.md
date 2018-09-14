# R1soft-installation
R1soft agent installation on CentOS6-7 and Ubuntu
Step 1 Create R1soft server

Step 2 Copy ssh key from the R1soft server to the remote hosts
ssh-copy-id

Step 3 Add hosts to the inventory file
cat hosts
[r1soft]
ipaddresses

Step 4 Run the playbook
ansible-playbook r1soft.yml
