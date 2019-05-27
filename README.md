## Infrastructure as Code with Ansible

## Apresentação

Administrar uma infraestrutura de DataCenter com a solução [Ansible](https://www.ansible.com) para automação.

Por que [Ansible](https://www.ansible.com)?

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
- [Guia Rápido](https://git.io/fhhZ9)

## Compatibilidade

  - [Fedora](https://getfedora.org/pt_BR/workstation/)
  - RHEL
  - CentOS
  - Debian
  - Ubuntu
  - Mac OS
  - Windows (WSL)?

# Requerimentos
  - Editores de texto 
    - [vim](https://aurelio.net/vim/)
    - atom
    - Visual Studio Code
-----------

## Ambiente

  - [Ansible](https://www.ansible.com) com [Travis CI](https://travis-ci.org/)
  - [Ansible](https://www.ansible.com) c/ [vagrant](https://www.vagrantup.com/)
  - [Ansible c/ docker](https://github.com/wluisaraujo/iac-ansible-docker.git)
  - [Ansible Galaxy](https://galaxy.ansible.com/)

  Utilizando [Ansible](https://www.ansible.com) para gerenciar configurações de servidores Linux (Debian/CentOs/Ubuntu), MS Windows nodes.

Roles para gerenciar um ambiente de infraestrutura

Role | Ansible Galaxy | Build
--- | --- | ---
[Desktop Linux](https://git.io/fjRaK) | 
[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Desktop%20Linux-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac_ansible_workstation_environment) | 
[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-workstation-environment.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-workstation-environment)
[Users Linux (local)](https://git.io/fjRao) | 
[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Desktop%20Linux-blue.svg)](https://git.io/fjRao) | 
[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-local-users.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-local-users)
[BaseLine de Servidores (Compliance)](https://github.com/wluisaraujo/iac-ansible-common-server.git) | 
[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Common%20Server-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-common-server) | 
[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-common-server.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-common-server)
[Firewall IPtables](https://github.com/wluisaraujo/iac-ansible-iptables.git) | 
[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Firewall%20IPtables-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-iptables) | 
[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-iptables.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-iptables)
[Servidor DHCP](https://github.com/wluisaraujo/iac-ansible-dhcp-server.git) | TEXTO | TEXTO
[VPN Server](http://dev/null)  | TEXTO | TEXTO
[NTP Server](https://github.com/wluisaraujo/iac-ansible-ntp-server.git)  | TEXTO | TEXTO
[NTP Client](https://github.com/wluisaraujo/iac-ansible-ntp-client.git)  | TEXTO | TEXTO
[Log Server](http://dev/null) | TEXTO | TEXTO
[Log Client](https://github.com/wluisaraujo/iac-ansible-rsyslog-client.git)
[NTP Server](http://dev/null) | TEXTO | TEXTO
[NTP Client](http://dev/null) | TEXTO | TEXTO
[SNMP Client](https://github.com/wluisaraujo/iac-ansible-snmp-agent.git)  | TEXTO | TEXTO  
[Servidor DNS](https://github.com/wluisaraujo/iac-ansible-named-server.git)  | TEXTO | TEXTO
[Servidor DNS Slave](https://github.com/wluisaraujo/iac-ansible-named-slave.git) | TEXTO | TEXTO
[Web Interface Gui](https://github.com/wluisaraujo/iac-ansible-globodns.git) | TEXTO | TEXTO
[Webserver](https://github.com/wluisaraujo/iac-ansible-webserver.git) | TEXTO | TEXTO
[MailServer](https://github.com/wluisaraujo/iac-ansible-postfix.git) | TEXTO | TEXTO
[WebMail](https://github.com/wluisaraujo/iac-ansible-roundcubemail.git) | TEXTO | TEXTO
[PostgreSQL Database Server](https://github.com/wluisaraujo/iac-ansible-postgresql.git) | TEXTO | TEXTO
[LDAP Server](https://github.com/wluisaraujo/iac-ansible-openldap.git) | TEXTO | TEXTO
[Proxy](https://github.com/wluisaraujo/iac-ansible-squid.git) | TEXTO | TEXTO
[Auditoria de Log de Proxy](https://dev/null) | TEXTO | TEXTO
[Servidor vsFTPd](https://github.com/wluisaraujo/iac-ansible-vsftpd.git) | TEXTO | TEXTO
[Puppet](https://github.com/wluisaraujo/iac-ansible-puppet-ce.git) | TEXTO | TEXTO
[GitLab](https://github.com/wluisaraujo/iac-ansible-gitlab.git) | TEXTO | TEXTO
[Ansible Tower & AWX](https://github.com/wluisaraujo/iac-ansible-awx.git) | TEXTO | TEXTO
[Rundeck](https://github.com/wluisaraujo/iac-ansible-rundeck.git) | TEXTO | TEXTO
[Jenkins](https://github.com/wluisaraujo/iac-ansible-jenkins.git) | TEXTO | TEXTO
[Foreman](https://github.com/wluisaraujo/iac-ansible-theforeman.git) | TEXTO | TEXTO

 



		
## Refrências
-----------

[Blog 4Linux](http://blog.4linux.com.br/)

[AnsibleBR](http://ansible-br.org)

[DevDocs](http://devdocs.io/ansible/)

[DoAUTO](https://doauto.blog/?s=ansible)

[Churrops](https://churrops.io/category/devops/ansible)

[Medium](https://medium.com/@ricardson)

[DigitalOcean](https://www.digitalocean.com)

[GiovanniReisNunes](https://giovannireisnunes.wordpress.com)

[Cyberciti](https://www.cyberciti.biz/faq/how-to-set-and-use-sudo-password-for-ansible-vault/)

----------------
[![Author](https://img.shields.io/badge/Author-%40w.luis.araujo-blue.svg)](http://linkedin.com/in/wluisaraujo)

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
