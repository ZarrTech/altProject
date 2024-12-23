Vagrant.configure("2") do |config|

    config.vm.define "altProject" do |altProject|
    altProject.vm.box = "ubuntu/bionic64"
        altProject.vm.hostname = "altProject"
        altProject.vm.network "private_network", ip: "192.168.12.4"
        altProject.vm.provider "virtualbox" do |vb|
        vb.memory = "2024"
        end
    end

end

