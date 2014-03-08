ansible-docker
==============

ansible role to manage Atlassian Stash docker container
=======
There's a bug using docker_images module on ansible 1.5 from CentOS epel repo    . Therefore install  ansible from github source is required.
  
git clone https://github.com/ansible/ansible.git

They have fixed the bug, please refer to:

https://github.com/ansible/ansible/pull/6196


Install ansible from source:

git clone https://github.com/ansible/ansible.git
cd ./ansible
sudo source ./hacking/env-setup
sudo easy_install pip
sudo pip install paramiko PyYAML jinja2 httplib2

