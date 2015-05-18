# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://atlas.hashicorp.com/search.

  config.vm.box = "centos6.6"
  config.vm.box_url = "https://s3-ap-northeast-1.amazonaws.com/indare-s3-bucket01/vagrant/centos66.box"
  config.vm.network :private_network, ip: "192.168.33.40", auto_config: false, virtualbox__intnet: "intnet"

  #変えてね！
  #config.vm.synced_folder "/Users/hoge/workspace", "/home/vagrant/workspace", owner: "vagrant", group: "vagrant"

  config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    # vb.gui = true

    # Customize the amount of memory on the VM:
    vb.memory = "1024"
  end

end
