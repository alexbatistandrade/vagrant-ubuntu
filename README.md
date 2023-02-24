# vagrant-ubuntu
Máquina virtual no vagrant do Ubuntu 20.04

#especificações da máquina
Placa em modo bridge

Memória ram: 1GB

CPU: 1

------------------------------------
Comandos utilizados para o projeto

#baixar a imagem
vagrant init Ubuntu/focal64

#iniciar a imagem no provider
vagrant up

#acessar a imagem via ssh
vagrant ssh

#alterar as especificações da máquina no arquivo Vagrantfile
vim Vagrantfile

#fazer o deploy da imagem com as alterações feita no arquivo Vagrantfile
vagrant reload

#destruir a maquina
vagrant destroy
