Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.provision :shell, path: "aptinstall.sh"
  config.vm.synced_folder "volume", "/volume"
end