Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
#  config.vm.box_url = "https://vagrantcloud.com/hashicorp/precise64"

    config.vm.network "private_network", type: "dhcp"
	config.vm.provision :shell, path: "bootstrap.sh"
end