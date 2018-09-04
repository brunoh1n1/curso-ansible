Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"
  config.vm.provider "virtualbox" do |v|
  v.memory = 512
  end

  config.vm.define "aulaalura" do |m|
  config.vm.network "private_network", ip: "10.20.200.213"
  end

end 
