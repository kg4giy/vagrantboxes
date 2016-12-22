# Vagrant Boxes

Work space for files and boxes related to my Vagrant exerciese

Sources:

https://blog.engineyard.com/2014/building-a-vagrant-box

CentOS does not enable networking by default (ugh)

In /etc/sysconfig/network-scripts, edit the ifcfg-interface and change `ONBOOT=no` to `ONBOOT=yes`

Networking: https://wiki.centos.org/FAQ/CentOS7