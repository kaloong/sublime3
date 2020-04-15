# sublime3
This playbook aims to install the awesome Sublime3 text editor on my Ubuntu desktop quickly and easily as per the install guide URL below.
https://www.sublimetext.com/docs/3/linux_repositories.html 

Of course, ensure that Ansible 2.9 is installed first.
( Haven't had a chance to test on older versions.)

To install Sublime 3211 on Ubuntu do:
ansible-playbook main.yml

For Download and unzip only do:
ansible-playbook main.yml -e "source=true"
