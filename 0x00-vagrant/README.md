# **0x00. Vagrant**
> ## *Foundations - 0-Day ― 0-Day*

## General
* What is a zero-day
* What is a virtual machine
* What is Vagrant
* Who wrote Vagrant
* What is Ubuntu
* What does “Ubuntu” mean
* How to use VMs with Vagrant
* What does the command uname do
* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code

### *Virtual machine*

In computing, a virtual machine (VM) is an emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination

## *Using Vagrant on your personal computer*

* Download VirtualBox from this [link](https://www.virtualbox.org/wiki/Downloads)
* Install VirtualBox
* Download Vagrant from this [link](https://www.vagrantup.com/downloads.html)
* Install Vagrant
* Open the Terminal application:
  * Now you will execute command line in your Terminal (each of them start with $)
  * Add the Ubuntu 14.04 (Trusty) image to your box list:
  > $ vagrant box add ubuntu/trusty64 
  * Many other images are available [here](https://app.vagrantup.com/boxes/search)
* Create your first virtual machine:
* **$ vagrant init ubuntu/trusty64** -> it will generate a Vagrantfile with **base = "ubuntu/trusty64"** - you don’t have to execute this command line everyday, only once, to create a new virtual machine
* **$ vagrant up** -> it will start your virtual machine
* **$ vagrant ssh** -> now you are inside your virtual machine.
* Open a terminal and run **vagrant box list** will print the list of boxes available on the computers.
* To initialize vagrant (create a Vagrantfile) run the following command: **vagrant init.**
* Open the file Vagrantfile with your favorite editor (probably Emacs or vi). Find the config.vm.box variable and replace base or any other value with your Ubuntu VM name, in this case ubuntu/trusty64. It should look something like this when you open the Vagrantfile for the fist time:

> #Every Vagrant development environment requires a box. You can search for   	       		     	      	  	       	      	    	       	    	      	       	    	     #boxes at https://atlas.hashicorp.com/search. 	      	       		       	   	                                                                                                  config.vm.box = "base"

Save your Vagrantfile and go back to your shell. Run vagrant up to start the virtual machine.