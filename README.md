# Oracle-Free-Tier
Como Instalar VPS Oracle e liberar portas


video explicativo
https://www.youtube.com/watch?v=xYF8Rr9ik7Q


ENTRAR E DEFINIR ACESSO ROOT:

sudo -i
bash <(wget -qO- https://raw.githubusercontent.com/leitura/senharoot/main/senharoot.sh)


ABRIR PORTAS SERVER ORACLE:

sudo apt-get update
sudo apt install firewalld 
sudo firewall-cmd --zone=public --permanent --add-port=22/tcp 
sudo firewall-cmd --reload 
sudo firewall-cmd --zone=public --list-ports



SCRIPT SSHPLUS:

apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/rodrigo12xd/SSHPLUS/master/Plus && chmod 777 Plus && ./Plus


video explicativo
https://www.youtube.com/watch?v=xYF8Rr9ik7Q
