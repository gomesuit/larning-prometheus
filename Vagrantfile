# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.3"

  config.vm.network "private_network", ip: "192.168.33.10"

  config.vm.provision "shell", inline: <<-SHELL
    curl -fsSL get.docker.com | sh
    systemctl start docker
    docker pull prom/node-exporter
    docker run --rm -d --name node_exporter -p 9100:9100 prom/node-exporter
  SHELL
end
