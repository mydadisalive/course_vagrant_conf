# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"
  config.vm.hostname = "test1.example.com"
  config.vm.network = "forwarded_port", guest: 80, host: 8000
#  config.vm.provision "ansible" do |ansible|
#    ansible.playbook = 'playbook.yml'
#  end
end
