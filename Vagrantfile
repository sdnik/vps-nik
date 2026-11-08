Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.network "private_network", auto_configure: false

  config.vm.provision "shell", inline: &lt;&lt;-SHELL
    echo "Hello, world!" &gt; /home/vagrant/hello.txt
  SHELL

end
