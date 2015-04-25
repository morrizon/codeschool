# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "codeschool"
  config.vm.network "private_network", ip: "10.19.78.101"
  config.vm.provider "virtualbox" do |vb|
    vb.name = "codeschool"
    vb.memory = "2048"
    vb.cpus = "2"
  end
end
