Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.hostname = "bharath-web-dev"
  config.vm.provision "shell", path: "nginx_provision_in_ubuntu.sh"
end
