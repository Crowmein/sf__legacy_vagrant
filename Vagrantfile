Vagrant.configure("2") do |config|
  config.vm.box = "generic/centos6"

  config.vm.provision "shell", inline: <<-SHELL
    sudo yum install -y postgresql postgresql-server postgresql-contrib
  SHELL
end