# configure Vagrant

Vagrant.configure("2") do |config|
    config.vm.provider "virtualbox"
    config.vm.box = "hashicorp/bionic64"
    config.vm.provision "shell", path: "https://raw.githubusercontent.com/kikitux/curl-bash/master/provision/go.sh"
  end