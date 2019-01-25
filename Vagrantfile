Vagrant.configure("2") do |config|
    config.vm.define "mysql" do |mysql_config|
        mysql_config.vm.box = "ubuntu/bionic64"
        mysql_config.vm.network "private_network", ip: "192.168.1.10"
        mysql_config.vm.provider "virtualbox" do |mysql_config_provider|
            mysql_config_provider.memory = 2048
        end
    end
end