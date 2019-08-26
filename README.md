# Vagrant Boxes

Work space for files and boxes related to my Vagrant exerciese

Do not put the box files in here. Put them in Atlas.

## Sources:

https://blog.engineyard.com/2014/building-a-vagrant-box

https://www.skoblenick.com/vagrant/creating-a-custom-box-from-scratch/

## Multiple Machines

https://www.vagrantup.com/docs/multi-machine/

https://blog.ipswitch.com/how-to-create-multi-machine-environments-with-vagrant

## CentOS does not enable networking by default (ugh)

* bento/centos-7.6 has fixed the networking issue. 

Building the box, you need to make some changes. In /etc/sysconfig/network-scripts, edit the ifcfg-interface and change 

	ONBOOT=no to ONBOOT=yes

Networking: https://wiki.centos.org/FAQ/CentOS7

## Boxes on Atlas:

https://atlas.hashicorp.com/boxes/search?utf8=✓&sort=&provider=&q=kg4giy