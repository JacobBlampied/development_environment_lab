# Development Environment Lab

## Description
This README file shows how to set up a virtual machine using Vagrant.

## Requirements

* VirtualBox
* Vagrant

## Instructiions

* Download VirtualBox.
* Cretate the root directory for this project.
* Run: 'vagrant init ubuntu-xenial64' in your console in the root directory you have just created.
* Open the vagrant file in your text editior  and add 'config.vm.network "private_network", ip: "192.168.10.157"'
* Run: 'vagrant up' to load the virtual machine.
* Run 'vagrant ssh' to be able to interact with the virtual machine.
* run: 'sudo apt-get update -y'.
* run 'sudo apt-get upgrade -y'.
* run: 'sudo apt-get install nginx -y' to install nginx.
* Check the connection has been established by running: 'curl 192.168.10.157'. You should see html script appear on the console.
* After you change anything, run: 'exit' and then 'vagrant up'.
