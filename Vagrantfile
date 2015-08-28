# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.require_version ">= 1.7.2"

Vagrant.configure(2) do |config|

  config.ssh.insert_key = true

  config.vm.box = "puphpet/debian75-x64" # This is actually a 7.8 image
  config.vm.box_check_update = false
  config.vm.define "subrosa_vm"

  config.vm.hostname = 'subrosa.local'
  config.vm.network "private_network", ip: "192.168.50.50"
  config.vm.network "forwarded_port", guest: 80, host: 50080, auto_correct: true
  config.vm.network "forwarded_port", guest: 443, host: 50443, auto_correct: true

  config.vm.provision :ansible do |ansible|
    ansible.playbook = "site.yml"
    ansible.extra_vars = { ansible_ssh_user: "vagrant" }
    # ansible.verbose = "vvvv"
  end

  config.vm.provider "virtualbox" do |vm|
    vm.name = "subrosa_vm"
  end
end
