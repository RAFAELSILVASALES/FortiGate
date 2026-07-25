# FortiGate
O **Fortinet FortiGate Firewall** é um dispositivo de segurança de rede de próxima geração que protege contra ameaças cibernéticas. Ele oferece recursos como VPN, controle de aplicações, filtro web e prevenção de intrusões (IPS). É amplamente utilizado em empresas para garantir a segurança, o monitoramento e o controle do tráfego de rede.



# LABS 

<a href="https://github.com/RAFAELSILVASALES/FortiGate/blob/main/VLAN.png?raw=true">VLAN</a>

Laboratório de Segmentação de Rede com VLANs

Neste laboratório foi implementada uma infraestrutura de rede segmentada utilizando VLANs, com o objetivo de organizar os dispositivos de acordo com suas funções, aumentar a segurança da rede e facilitar o gerenciamento do ambiente.

Foram criadas três VLANs distintas:

VLAN 10 (192.168.10.0/24) destinada aos servidores, onde foram configurados um servidor Linux e um servidor adicional para simular serviços de rede.
VLAN 20 (192.168.20.0/24) destinada aos usuários, representada por um host Linux simulando uma estação de trabalho.
VLAN 30 (192.168.30.0/24) destinada ao gerenciamento e monitoramento, contendo um servidor Zabbix responsável pelo monitoramento da infraestrutura.

O switch foi configurado para realizar a segmentação da rede por meio das VLANs, com cada porta configurada em modo access e associada à VLAN correspondente. Dessa forma, os dispositivos permanecem isolados em seus respectivos domínios de broadcast.

O switch foi conectado a um firewall FortiGate, responsável pelo roteamento entre as VLANs (Inter-VLAN Routing) e pelo acesso à Internet. Essa configuração permite controlar a comunicação entre os diferentes segmentos da rede por meio de políticas de segurança, além de fornecer conectividade externa para os dispositivos autorizados.

Com esse laboratório foi possível praticar conceitos fundamentais de redes, como criação e configuração de VLANs, segmentação de tráfego, configuração de portas access, integração entre switch e firewall, roteamento entre VLANs e organização de uma infraestrutura de rede baseada em boas práticas utilizadas em ambientes corporativos. Além disso, a implementação de um servidor Zabbix na VLAN de gerenciamento permitiu compreender a importância do monitoramento contínuo dos dispositivos e serviços da rede, tornando o ambiente mais próximo de um cenário real de produção.
