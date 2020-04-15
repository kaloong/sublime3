# sublime3
This playbook aims to install Sublime3 on Ubuntu desktop quickly and easily as per the below install guide.
https://www.sublimetext.com/docs/3/linux_repositories.html 

To install Sublime 3211 on Ubuntu do:
ansible-playbook main.yml

For Download and unzip only do:
ansible-playbook main.yml -e "source=true"
