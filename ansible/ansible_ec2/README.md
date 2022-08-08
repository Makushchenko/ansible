ansible-inventory -i ./ansible_ec2/aws_ec2.yaml --list

ansible-inventory -i ./ansible_ec2/aws_ec2.yaml --graph 

ansible tag_Name_ansible_debian -m ping --private-key /home/oleksandr/.ssh/ansible.pem -u ubuntu


#-----------------------
inventory = ./ansible_ec2/aws_ec2.yaml