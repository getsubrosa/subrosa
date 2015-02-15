# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "base"
  config.vm.box_check_update = false
  config.vm.network "forwarded_port", guest: 80, host:50808
  config.vm.network "private_network", ip: "192.168.33.50"
  config.vm.synced_folder "./", "/vagrant_sub_rosa"

end
