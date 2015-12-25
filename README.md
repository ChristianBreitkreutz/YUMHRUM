# How to install YUMHRUM on centos from Ubuntu.

## Call init.sh as root.
It will install ansible.
`. init.sh`
 - `sudo apt-get install software-properties-common`
 - `sudo apt-add-repository ppa:ansible/ansible`
 - `sudo apt-get update`
 - `sudo apt-get install ansible`

## Install ESF + Docker + Centos.
 - `ansible-playbook -i epinventory.ini epages.yml --ask-sudo-pass`

## Install ePages on Centos.
 - `ansible-playbook -i inventory.ini centos.yml`
