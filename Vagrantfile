Vagrant.configure("2") do |config|

  config.vm.define "apps" do |apps|
    apps.vm.box = "debian/bookworm64"
    apps.vm.hostname = "apps.sistema.test"
    apps.vm.network "private_network", ip: "192.168.57.20"
    apps.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.name = "apps"
    end
  end

end
