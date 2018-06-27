# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"



Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

#Misma clave para todas las máquinas
config.ssh.insert_key = false

 config.vm.define "host" do |host|
  host.vm.hostname = "host"
  host.vm.box = "centos/7"
  host.ssh.username = "vagrant"
  #host.vm.network "forwarded_port", guest: 8080, host: 8080 
  #host.vm.provider :virtualbox do |vb|
   #vb.customize ["modifyvm", :id, "--nic2", "intnet"]
  #end
 
 end
end
