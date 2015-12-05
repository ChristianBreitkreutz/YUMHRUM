# How to install YUMHRUM on centos from Ubuntu.

## Call init.sh as root.
It will install ansible.
`. init.sh`
 - `sudo apt-get install software-properties-common`
 - `sudo apt-add-repository ppa:ansible/ansible`
 - `sudo apt-get update`
 - `sudo apt-get install ansible`

## Trigger install.
 - `ansible-playbook -i inventory.ini rush.yml`
  - `enter github account`
  - `enter github password`
