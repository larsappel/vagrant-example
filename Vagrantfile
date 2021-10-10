# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define vm_name = "MyServer" do |srv|
    srv.vm.hostname = vm_name
    srv.vm.box = "ubuntu/focal64"
    srv.vm.network "private_network", ip: "10.10.10.10"
    srv.vm.provision "shell", inline: <<-SHELL
    SHELL
  end
end
