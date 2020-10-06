**Objetivo**
-------------

- Instalar o agent do Zabbix nos servidores Windows 

=============================================================

 ![doc](https://github.com/leosp1983/zabbix-for-windows/blob/main/doc/ansible.png)

**Funções**
-------------

- [X] Cria o diretório do agent Zabbix;
- [X] Cria o share do diretório;
- [X] Distribui o agent no parque Windows; 
- [X] Distribui o template de configuração no parque Windows;
- [X] Instalação, start e validação do serviço do agent Zabbix;
- [X] Adiciona o hostname no Zabbix-server ou Zabbix proxy.

**Compatibilidade**
-------------

- [X] Windows server 2008; (Necessário atualização do powershell para no mínimo 3.0)
- [X] Windows server 2012;
- [X] Windows server 2016;
- [X] Windows server 2019.

**Opção para distribuição do agent**
-------------

- [X] Download
- [x] Network share

* Verifique qual opção melhor se adequa ao seu parque de servidores e ajuste as tasks no arquivo zabbix.yml
