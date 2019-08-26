# Vagrant file for Chef machines.

config.vm.define "chef" do |chef|
    chef.vm.box = "bento/centos-7.6"
    chef.vm.network "private_network", ip: "192.168.33.10"
    chef.vm.hostname = "chef-master"
end

config.vm.define "chef-guest1" do |chefguest1|
    chefguest1.vm.box = "bento/centos-7.6"
    chef.vm.network "private_network", ip: "192.168.33.11"
    chef.vm.hostname = "chef-guest1"
end

config.vm.define "chef-guest2" do |chefguest2|
    chefguest1.vm.box = "bento/centos-7.6"
    chef.vm.network "private_network", ip: "192.168.33.22"
    chef.vm.hostname = "chef-guest2"
end
