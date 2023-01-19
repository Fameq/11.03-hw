Vagrant.configure("2") do |config|
config.vm.define "master" do |master|
  master.vm.box = "ubuntu/bionic64"
  master.vm.hostname = "master"
  master.vm.network "public_network", ip: "192.168.1.123"
  master.vm.provider "virtualbox" do |vb|
      vb.memory = 8192
      vb.cpus = 4
  end
end
end
