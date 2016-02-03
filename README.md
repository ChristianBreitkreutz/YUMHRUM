# How to install YUMHRUM on Ubuntu

## Fill in your private data in
  - group_vars/all/main.yml
    - ansible_ssh_pass: ***
    - gitHubUserName: ***
    - gitHubPassword: ***

## Install commons and ESF container
 - `ansible-playbook -i inventory.ini site.yml`

## TODO: Install ePages on Centos.
 - `ansible-playbook -i centos.ini centos.yml`

## Run Jenkins container
 - `ansible-playbook -i inventory.ini jenkins.yml`
