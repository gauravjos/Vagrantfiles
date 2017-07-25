# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  config.vm.define "mesos" do |mesos| 
  	mesos.vm.box = "ubuntu/trusty64"
  	mesos.vm.network "public_network" , :adapter=>2 , type: "static", ip: "172.27.59.21", :bridge => "eth0"
  	mesos.vm.hostname ="mesos"
  	mesos.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
    vb.gui = true
    vb.name = "mesos"
     # Customize the amount of memory on the VM:
    vb.memory = "2048"
    end  
#    	mesos.vm.provision "chef_client" do |chef|
#     chef.chef_server_url = "https://api.chef.io/organizations/devops_testorg"
#     chef.validation_key_path = "devops_testorg-validator.pem"
#     chef.client_key_path  = "gauravjos.pem"
#     chef.validation_client_name = "devops_testorg-validator"
#     chef.node_name = "mesos-lb"
#     # chef.add_node = true
#  #   chef.cookbooks_path = "cookbooks"
# 	#chef.add_recipe  "apache2::default" 
# #	end
#   	end

 end
                                                                                                                                                                                                                                                                           


end
