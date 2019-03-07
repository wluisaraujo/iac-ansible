## Infrastructure as Code with Ansible

## Apresentação

Administrar uma infraestrutura de DataCenter com a solução ansible para automação.

Por que Ansible?
Entre as ferramentas, é a menos que interfere entre você e o problema. É a mais efetiva para traduzir o pensamentos em ações.
É All-in-one;
Faz Gerência de Configuração;
Aplica-se com idempotência;
Aplica-se a Convergência;
Mantêm o estado desejado;
Faz Provisionamento;
Integra-se há Orquestração;

-----------    

## Introdução
- [Guia Rápido](https://github.com/wluisaraujo/iac-ansible/blob/master/WELCOME.md)

## Compatibilidade

  - Fedora
  - RHEL
  - CentOS
  - Debian
  - Ubuntu
  - Mac OS
  - Windows (WSL)?

# Requerimentos
  - Editores de texto 
    - vim
    - atom
    - Visual Studio Code
-----------

## Ambiente

  - Ansible com Travis CI
  - Ansible c/ vagrant
  - [Ansible c/ docker](https://github.com/wluisaraujo/iac-ansible-docker.git)
  - Ansible Galaxy

  Utilizando ansible para gerenciar configurações de servidores Linux (Debian/CentOs/Ubuntu), MS Windows nodes.
Gerenciar um ambiente de infraestrutura utilizando serviços:

* Ambiente Desktop
  * [Desktop Linux]
  * [Users Linux (local)](https://github.com/wluisaraujo/iac-ansible-local-users.git)

* [BaseLine de Servidores (Compliance)](https://github.com/wluisaraujo/iac-ansible-common-server.git)

* Servidores de Rede
  * [Firewall IPtables](https://github.com/wluisaraujo/iac-ansible-iptables.git)
  * [Servidor DHCP](https://github.com/wluisaraujo/iac-ansible-dhcp-server.git)
  * [VPN Server](http://dev/null)
  * [NTP Server](https://github.com/wluisaraujo/iac-ansible-ntp-server.git)
  * [NTP Client](https://github.com/wluisaraujo/iac-ansible-ntp-client.git)
  * [Log Server]
  * [Log Client](https://github.com/wluisaraujo/iac-ansible-rsyslog-client.git)
  * [NTP Server]
  * [NTP Client]
  * [SNMP Client](https://github.com/wluisaraujo/iac-ansible-snmp-agent.git)
  
* Servidores DNS
  * [Servidor DNS]
  * [Servidor DNS Slave](https://github.com/wluisaraujo/iac-ansible-named-slave.git)
  * [Web Interface Gui](https://github.com/wluisaraujo/iac-ansible-globodns.git)
  
*  Servidores Web
   * [Webserver](http://localhost)
   
* Servidor de E-mail   
   * [MailServer](https://github.com/wluisaraujo/iac-ansible-postfix.git)
   * [WebMail](https://github.com/wluisaraujo/iac-ansible-roundcubemail.git)
   
* Servidor de Banco de Dados   
  * [PostgreSQL Database Server](https://github.com/wluisaraujo/iac-ansible-postgresql.git)
  
* Servidor de Autenticação
  * [LDAP Server]
  
* Servidor de Storage e Compartilhamento
  * [Storage]
  * [File Server]
  
* Servidor de Proxy  
  * [Proxy](https://github.com/wluisaraujo/iac-ansible-squid.git)
  * [Auditoria de Log de Proxy](https://dev/null)
  
* Servidor de FTP
  * [Servidor vsFTPd](https://github.com/wluisaraujo/iac-ansible-vsftpd.git)

* Orquestração de Ambientes Infraestrutura
  * [Puppet](https://github.com/wluisaraujo/iac-ansible-puppet-ce.git)
  
-----------

## Integração

  - Interface Web
  - [Ansible Tower & AWX](https://github.com/wluisaraujo/iac-ansible-awx.git)
  - [Rundeck](https://github.com/wluisaraujo/iac-ansible-rundeck.git)
  - [Jenkins](https://github.com/wluisaraujo/iac-ansible-jenkins.git)
  - Project ARA
		
## Refrências
-----------

* http://blog.4linux.com.br/
* http://ansible-br.org
* http://devdocs.io/ansible/
* https://doauto.blog/?s=ansible
* https://churrops.io/category/devops/ansible
* https://medium.com/@ricardson
* http://blog.4linux.com.br
* https://www.digitalocean.com
* https://giovannireisnunes.wordpress.com
* https://www.cyberciti.biz/faq/how-to-set-and-use-sudo-password-for-ansible-vault/

## Author
-----------
* [LUSAR](http://linkedin.com/in/wluisaraujo)
