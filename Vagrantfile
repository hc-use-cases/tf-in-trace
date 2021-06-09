# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "apopa/bionic64"
  config.vm.hostname = "tf-in-trace"
  config.vm.provision "shell", path: "https://raw.githubusercontent.com/andrewpopa/bash-provisioning/main/terraform/latest.sh"
end
