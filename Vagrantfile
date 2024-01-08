Vagrant.configure("2") do |config|

  config.vm.define "ansible-c" do |ansible|
    ansible.vm.box = "generic/rhel9"
	ansible.vm.network "private_network", ip: "192.168.56.70"
	ansible.vm.provider "virtualbox" do |vb|
    config.vm.provider "virtualbox" do |v|
       v.memory = 2048
       v.cpus = 2
    end
   end
  end

  config.vm.define "node01" do |node01|
    node01.vm.box = "generic/rhel9"
	node01.vm.network "private_network", ip: "192.168.56.71"
    config.vm.provider "virtualbox" do |v|
        v.memory = 1048
        v.cpus = 1
     end
  end
  
  config.vm.define "node02" do |node02|
    node02.vm.box = "generic/rhel9"
	node02.vm.network "private_network", ip: "192.168.56.72"
     config.vm.provider "virtualbox" do |v|
        v.memory = 1048
        v.cpus = 1
     end
  end

   config.vm.define "node03" do |node03|
    node03.vm.box = "generic/rhel9"
        node03.vm.network "private_network", ip: "192.168.56.73"
     config.vm.provider "virtualbox" do |v|
        v.memory = 1048
        v.cpus = 2
     end
  end

  config.vm.define "node04" do |node04|
    node04.vm.box = "generic/rhel9"
	node04.vm.network "private_network", ip: "192.168.56.74"
     config.vm.provider "virtualbox" do |v|
        v.memory = 1048
        v.cpus = 1
     end
  end

  config.vm.define "node05" do |node05|
    node05.vm.box = "generic/rhel9"
	node05.vm.network "private_network", ip: "192.168.56.75"
     config.vm.provider "virtualbox" do |v|
        v.memory = 1048
        v.cpus = 1
     end
  end


end

