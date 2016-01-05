# How to install YUMHRUM on CentOS

## Call init.sh as root.
It will install ansible.
`. init.sh`
 - `yum install epel-release.noarch`
 - `yum install ansible`

## Fill in your private data in
  - group_vars/all/main.yml
    - ansible_ssh_pass: ***
    - gitHubUserName: ***
    - gitHubPassword: ***

## Install Docker with CentOS and ESF containers
 - `ansible-playbook -i inventory.ini site.yml`

## TODO: Install ePages on Centos.
 - `ansible-playbook -i centos.ini centos.yml`

## Run Jenkins container
 - `ansible-playbook -i inventiry.ini jenkins.yml`
