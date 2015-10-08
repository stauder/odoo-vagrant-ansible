# odoo-vagrant-ansible
Installs odoo in Vagrant with the help of anybox.recipe.odoo

# One time tasks
## install ansible
```bash
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

## Tasks to start the virtual machine
```bash
git clone git://github.com/stauder/odoo-vagrant-ansible.git
vagrant up
```

## Task to provision (reexecute the ansible config)
```bash
vagrant provision
```

