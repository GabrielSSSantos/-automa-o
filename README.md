# Estalação é configuração do Zabbix Agent

Altere "servidores-linux.ini" de acordo com os IPs dos Servidores a serem configurados.

Altere "replace:" para o IP do seu Zabbix Proxy ou Zabbix Server, dependendo do sua infraestrutura.


Comando para executar o playbook:
sudo ansible-playbook -i servidores-linux.ini playbook-ZabbixAgent.yml --ask-become-pass
