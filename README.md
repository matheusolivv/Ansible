# Ansible
Ansible

Código fornecido no treinamento da Iaas Week da LinuxTips para instalação do k8s no Ubuntu, foi realizado alguns ajustes para rodar no centos7.

É necessário editar o arquivo hosts e adicionar o IP do master na tag [k8s-master] de acordo com seu ambiente

[k8s-master]\n
192.168.0.10

Editar o arquivo hosts e adicionar os IP's dos workers na tag [k8s-workers] de acordo com seu ambiente
[k8s-workers]\n
192.168.0.20\n
192.168.0.21