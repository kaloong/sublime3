# sublime3

This playbook aims to install the awesome Sublime3 text editor on my Linux VM/machines quickly and easily as per the install guide URL below.
https://www.sublimetext.com/docs/3/linux_repositories.html 

Of course, ensure that Ansible 2.9 is installed first.
( Haven't had a chance to test any older versions.)

To install Sublime version 3211 on Ubuntu or CentOS do:

- ansible-playbook main.yml

It should detect OS release and run accordingly.

For Download and unzip only do:
- ansible-playbook main.yml -e "source=true"

Or

- ansible-playbook main.yml -e "source="

If running on CentOS system, append -K for sudo password.
- ansible-playbook main.yml -e "source=" -K

It doesn't matter what 'source' is defined as, as long as it is defined, it can then trigger Download/unzip section.

# todo:

- Include stable and dev url as variable in a separate file.
- See if it should be converted into role?

