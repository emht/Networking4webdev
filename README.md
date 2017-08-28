## This repository contains the details of the online course I took on udacity on "Networking for Web Developers"

    It contains the details regarding the specification and the software packages I installed to learn this domain of knowledge and to improvise this field of my knowledge.

* I could have set services like Amazon Saillight or virtualbox for this. (I chose VirtualBox)

* Install VirtualBox and Vagrant for it to work.
	* Download the .deb package for virtualbox
	* Install all the dependencies required for it to work
	* Install virtualBox using sudo apt install ./\*.deb
	* OR, you can just install it via your distros package manager or add the official virtualbox repostiory in your default repository lists, and then add the key to authenticate its use.
	*
	* For Vagrant use package manager of your linux distro or refer their website

* Initialise a vagrant environment, so that you can create, share and distribute your virtualenvironment. (Please refer the man page for vagrant to know more.)
	`vagrant init ubuntu/trusty64`

	`vagrant up`

* Enter the shell of that virtual machine using ssh, it remotely connects your host computer to a remote computer or a virtual machine on your computer
	`vagrant ssh`

* Install all the network tools for your remote commputer, but first update your system by: 
	`sudo apt update && sudo apt upgrade`: debian
	`sudo apt install netcat-openbsd tcpdump traceroute mtr`
	`sudo apt install wireless-tools` : optionally (only I did)
* 












(**Note:** The course link is as: https://classroom.udacity.com/courses/ud256/lessons/7090748708/concepts/70968590280923, Try it, its very well documented)
