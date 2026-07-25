# FortiGate
O **Fortinet FortiGate Firewall** é um dispositivo de segurança de rede de próxima geração que protege contra ameaças cibernéticas. Ele oferece recursos como VPN, controle de aplicações, filtro web e prevenção de intrusões (IPS). É amplamente utilizado em empresas para garantir a segurança, o monitoramento e o controle do tráfego de rede.


                Internet
                    │
              FortiGate
                    │ trunk
               ┌──────────┐
               │ Switch   │
               └──────────┘
      ┌──────────┼───────────┐
      │          │           │
   VLAN10     VLAN20      VLAN30
 Servidores   Usuários   Gerência

Linux Web      PC1        Zabbix
Servidor DB    PC2        Syslog
DNS            PC3
