Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
	config.vm.network "public_network", ip: "192.168.1.60"
	config.vm.provision :shell, path: "bootstrap.sh"
end