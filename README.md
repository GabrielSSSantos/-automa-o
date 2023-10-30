## Instalação e Configuração do Zabbix Agent

### Passos:

1. **Edição do arquivo "servidores-linux.ini":**  
   Altere este arquivo para incluir os IPs dos servidores que deseja configurar.

2. **Configuração do endereço IP no arquivo:**  
   Encontre a seção "replace:" e insira o IP do seu Zabbix Proxy ou Zabbix Server, dependendo da sua infraestrutura.

### Comando para executar o playbook:

```bash
sudo ansible-playbook -i servidores-linux.ini playbook-ZabbixAgent.yml --ask-become-pass

