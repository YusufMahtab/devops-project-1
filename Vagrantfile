# -*- mode: ruby -*-
# vi: set ft=ruby :

# Don't change the "2" in Vagrant.configure
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.box_version = "1.0.282"

  # Run bootstrap.sh on startup
  config.vm.provision :shell, path: "scripts/bootstrap.sh"

  # Port forwarding
  config.vm.network :forwarded_port, guest: 80, host: 4567
end
