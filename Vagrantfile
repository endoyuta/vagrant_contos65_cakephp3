# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "centos6.5.3"
  config.vm.box_url = "https://github.com/2creatives/vagrant-centos/releases/download/v6.5.3/centos65-x86_64-20140116.box"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.synced_folder "./", "/vagrant", mount_options: ['dmode=777', 'fmode=666']
end
