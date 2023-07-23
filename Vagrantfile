Vagrant.configure("2") do |config|
  config.vm.box = "gusztavvargadr/windows-server-2022-standard"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"
    vb.cpus = 4
  end
  config.vm.hostname = "win2022"
  config.vm.network "private_network", ip: "192.168.33.10"
end
