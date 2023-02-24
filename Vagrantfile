Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.hostname = "vagrant-alex"
   config.vm.network "public_network"

  config.vm.provider "virtualbox" do |vb|
     vb.memory = "1024"
     vb.cpus ="1"

  end
end
