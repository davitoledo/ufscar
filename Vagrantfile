Vagrant.configure("2") do |config|
  config.vm.define "monitoring" do |svr|
    svr.vm.box = "centos/7"
      svr.vm.provider "virtualbox" do |vb|
        vb.name = "monitoring"
        vb.memory = 2048
        vb.cpus = 1
      end
  end
end
