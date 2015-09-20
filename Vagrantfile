# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"


Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "box-cutter/ubuntu1404-desktop"
  config.vm.network "private_network", ip: "192.168.98.3"

  # bug ip adress not set up properly on Desktop Ubuntu
  # workaround: VBoxManage dhcpserver remove --netname HostInterfaceNetworking-vboxnet0

end