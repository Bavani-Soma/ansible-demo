Vagrant.configure("2") do |config|
 config.vm.define "webserver" do |webserver|
  config.vm.box = "ubantu/trusty64"
  config.vm.hostname = "webserver"
  config.vm.network :private_network, ip: "192.168.0.2"
 end
 config.vm.define "ansible" do |ansible|
  config.vm.box = "ubantu/trusty64"
  config.vm.hostname = "ansible"
  config.vm.network :private_network, ip: "192.168.0.254"
 end
end

