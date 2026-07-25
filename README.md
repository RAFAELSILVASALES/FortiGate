# FortiGate
O **Fortinet FortiGate Firewall** é um dispositivo de segurança de rede de próxima geração que protege contra ameaças cibernéticas. Ele oferece recursos como VPN, controle de aplicações, filtro web e prevenção de intrusões (IPS). É amplamente utilizado em empresas para garantir a segurança, o monitoramento e o controle do tráfego de rede.



# LABS 


<img src="https://github.com/RAFAELSILVASALES/FortiGate/blob/main/VLAN.png?raw=true" alt="LABS">


Laboratório de Segmentação de Rede com VLANs

Neste laboratório foi implementada uma infraestrutura de rede segmentada utilizando VLANs, com o objetivo de organizar os dispositivos de acordo com suas funções, aumentar a segurança da rede e facilitar o gerenciamento do ambiente.

Foram criadas três VLANs distintas:

VLAN 10 (192.168.10.0/24) destinada aos servidores, onde foram configurados um servidor Linux e um servidor adicional para simular serviços de rede.
VLAN 20 (192.168.20.0/24) destinada aos usuários, representada por um host Linux simulando uma estação de trabalho.
VLAN 30 (192.168.30.0/24) destinada ao gerenciamento e monitoramento, contendo um servidor Zabbix responsável pelo monitoramento da infraestrutura.

O switch foi configurado para realizar a segmentação da rede por meio das VLANs, com cada porta configurada em modo access e associada à VLAN correspondente. Dessa forma, os dispositivos permanecem isolados em seus respectivos domínios de broadcast.

O switch foi conectado a um firewall FortiGate, responsável pelo roteamento entre as VLANs (Inter-VLAN Routing) e pelo acesso à Internet. Essa configuração permite controlar a comunicação entre os diferentes segmentos da rede por meio de políticas de segurança, além de fornecer conectividade externa para os dispositivos autorizados.

#--------------------------------------------------------------------------------------------------------------------------#
<img src="https://github.com/RAFAELSILVASALES/FortiGate/blob/main/SD-WAN.png?raw=true" alt="LABS">
Laboratório Prático de SD-WAN com FortiGate
Implementação de um ambiente de laboratório utilizando FortiGate integrado a dois provedores de Internet (CLARO e VIVO), com configuração de múltiplos links WAN e estudo comparativo entre ECMP e SD-WAN. O laboratório abordou seleção dinâmica de caminhos, monitoramento de qualidade dos links, disponibilidade, balanceamento de tráfego e failover entre diferentes conexões de Internet.

Tecnologias/conceitos envolvidos
FortiGate / Fortinet
SD-WAN
ECMP
Múltiplos links WAN
Failover
Balanceamento de tráfego
Monitoramento de latência
Jitter
Perda de pacotes
Políticas de SD-WAN
Roteamento
Dois provedores de Internet (CLARO e VIVO)

Com esse laboratório foi possível praticar conceitos fundamentais de redes, como criação e configuração de VLANs, segmentação de tráfego, configuração de portas access, integração entre switch e firewall, roteamento entre VLANs e organização de uma infraestrutura de rede baseada em boas práticas utilizadas em ambientes corporativos. Além disso, a implementação de um servidor Zabbix na VLAN de gerenciamento permitiu compreender a importância do monitoramento contínuo dos dispositivos e serviços da rede, tornando o ambiente mais próximo de um cenário real de produção.


#----------------------------------------------------------------------------------------------------------------#
<img src="https://github.com/RAFAELSILVASALES/FortiGate/blob/main/Police.png?raw=true" alt="LABS">

Laboratório de SD-WAN com FortiGate e múltiplos provedores: Implementação de uma topologia com dois FortiGate e dois provedores de Internet (CLARO e VIVO), configurando políticas de SD-WAN para direcionamento inteligente do tráfego. Foi realizada a definição de regras para que o tráfego originado pelos servidores utilizasse preferencialmente o link da VIVO, explorando conceitos de seleção de caminho, roteamento baseado em políticas e utilização de múltiplos links WAN.

#----------------------------------------------------------------------------------------------------------------------------#

<img src="https://github.com/RAFAELSILVASALES/FortiGate/blob/main/VPN.png?raw=true" alt="LABS">
Laboratório de VPN Site-to-Site com FortiGate: Configuração de uma VPN Site-to-Site utilizando FortiGate para estabelecer uma comunicação segura entre duas redes distintas através de um enlace, permitindo a conectividade entre os dispositivos das redes locais dos dois sites.
