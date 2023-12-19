Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"  # Используем Ubuntu 18.04

  config.vm.provision "shell", inline: <<-SHELL
    # Обновление списка пакетов
    sudo apt-get update

    # Установка PostgreSQL 8.4
    sudo apt-get install -y postgresql-8.4
  SHELL
end
