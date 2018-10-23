Vagrant.configure("2") do |config| 
 config.vm.define "var" do |var| 
  var.vm.box = "ubuntu/trusty64" 
  var.vm.hostname = "var.vagrant.test"
  var.vm.network "public_network", ip: "192.168.1.60"
  var.vm.provision :shell, path: "bootstrap.sh"  

  var.vm.provider :virtualbox do |v| 
   v.customize ["modifyvm", :id, "--memory", "1024"]
  end

 end 
end

