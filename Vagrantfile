Vagrant::Config.run do |config|
    config.vm.box = "lucid32"
    config.vm.forward_port 80, 3000
    config.vm.provision :puppet
end
