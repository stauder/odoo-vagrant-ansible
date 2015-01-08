# odoo-vagrant-ansible
Installs odoo in Vagrant with the help of anybox.recipe.odoo


##############
# One time tasks

# install ansible
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible

# Download vagrant box
vagrant box add precise32 http://files.vagrantup.com/precise32.box

# End of the one time tasks
##############

##############
# Tasks to start the virtual machine

git clone git://github.com/stauder/odoo-vagrant-ansible.git
mkdir data
vagrant up

# End of the tasks to start a virtual machine
##############

