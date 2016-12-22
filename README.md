# Vagrant Boxes

Work space for files and boxes related to my Vagrant exerciese

Do not put the box files in here. Put them in Atlas.

Sources:

https://blog.engineyard.com/2014/building-a-vagrant-box

https://www.skoblenick.com/vagrant/creating-a-custom-box-from-scratch/

CentOS does not enable networking by default (ugh)

In /etc/sysconfig/network-scripts, edit the ifcfg-interface and change `ONBOOT=no` to `ONBOOT=yes`

Networking: https://wiki.centos.org/FAQ/CentOS7

https://atlas.hashicorp.com/switchco/boxes/EdgeController_voip