# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "debian/jessie64"

  config.vm.network "public_network", bridge: "en1: Wi-Fi (AirPort)"

  config.vm.provision :shell, path: "bootstrap.sh"

end
