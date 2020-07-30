
# Demo-CICD

> This is a demo for an effective software CICD



# Git

* git clone https://github.com/jorgehas/Demo-CICD.git

* $ git add test.txt
* $ git commit -m "Added a test file"
* $ git commit -m "Added a test file"
### Adding feature branch
* $ git checkout cicd-features
* $ echo "cicd-features" > cicd-features.txt
* $ git add cicd-features.txt
* $ git commit -m "added new feature in cicd feature branch

### Pushing into the new feature branch

* $ git push origin cicd-features

### Merge feature branch into master

* $ git checkout master
* $ git merge cicd-features

## Vagrant
Vagrant provisioning

* $ mkdir vagrantProvision
##### Provision with Ubuntu 14.04

* $ cd vagrantProvision/
* $ vagrant init ubuntu/trusty64
##### start

* $ vagrant up
##### Stop
* $ vagrant halt

 ## Ansible

 
