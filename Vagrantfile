Vagrant.configure("2") do |config|
  config.vm.box = "Suzu/rails-tutorial"
  config.vm.box_version = "2019.06.07"
  config.vm.network "forwarded_port", guest: 3000, host: 3000
  config.vm.synced_folder "./data", "/vagrant_data"
  config.vm.provider "virtualbox" do |vb|
    vb.cpus = 1
    vb.memory = 1024
  end
end
