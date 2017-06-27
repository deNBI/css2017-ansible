# Course Repository for the de.NBI workshop "Introduction to automated infrastructure management with Ansible"

Authors: Manuel Prinz, Philip R. Kensche

## Basic Setup

The course requires at least a Debian and a CentOS target systems to configure. However, for the de.NBI course there is an additional management VM in the OpenStack. Therefore, at the beginning of the hands-on session you should start 3 VMs based on the following 3 images:

1. "css-ansible-box_2017-06-14": The management node. This is basically a CentOS VM with Ansible pre-installed. This VM should get a floating IP such that you can log in with SSH and carry out the commands during the exercises.
1. "Debian 9.0 (Stretch)": Target VM "vm1" to configure.
1. "CentOS 7 (1705)": Target VM "vm2" to configure.

After logging in to the management VM, you should clone this repo:

   git clone https://github.com/deNBI/css2017-ansible.git
   
