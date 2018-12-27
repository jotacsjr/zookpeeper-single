# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|

  config.ssh.insert_key = false
	
  config.vm.define "zookeeper-single" do |node|
    node.vm.box = "ubuntu/xenial64"
    node.vm.host_name = "zookeeper-single"
    node.vm.network "private_network", ip: "192.168.2.11"
    node.vm.provider "virtualbox" do |vb|
      vb.cpus = 1
      vb.memory = "2048"
    end
  end
end    
	

