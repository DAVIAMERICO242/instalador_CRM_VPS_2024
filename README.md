####MANUAL:

//TUTORIAL
https://www.youtube.com/watch?v=X5VK3NamWrY&ab_channel=VemFazer
//LOGIN
Usuário: admin@whaticket.com
Senha: admin
//REEXECUTAR OS SEGUINTES COMANDOS DEPOIS DA INSTALAÇÃO
sudo certbot --nginx

ssh-keygen -R 154.12.225.62
sudo apt update && sudo apt upgrade
sudo apt install iptables
sudo iptables -A INPUT -p tcp --dport 3000 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 4000 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 5000 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 443 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 3003 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 8080 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 8088 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT
sudo iptables-save
ssh root@154.12.225.62
senha do ssh

fazer: https://github.com/ctichat/instaladorvemfazer(pode ser o instalador do meu github)
usando o modelo crm: https://github.com/unkbot/whaticket-free (pode ser o crm do meu github)


FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/ctichat/instaladorvemfazer install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./install && sudo ./install_instancia
```

