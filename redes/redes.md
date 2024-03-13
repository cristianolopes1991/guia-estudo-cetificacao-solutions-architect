## Redes

### Amazon VPC

Uma virtual private cloud (VPC) é uma rede isolada que você cria na Nuvem AWS, semelhante a uma rede tradicional em um datacenter. Ao criar uma VPC, você deve escolher três fatores principais. 

    - Nome da VPC
    - Região em que a VPC ficará ativa. Cada VPC abrange várias zonas de disponibilidade dentro da região selecionada.
    - Intervalo de IP para a VPC na notação CIDR. Isso determina o tamanho real da rede. Cada VPC pode ter até quatro intevado de IP/16.


Underestanding CIDR - IPv4
    - Classless Inter-Domain Routing - a method for allocating IP addresses
    - Used in Security Groups rules and AWS networking in general 

    - They help to define an IP address range:
        - We've seen WW.XX.YY.ZZ/32 => one IP

    - A CIDR consists of two components
    - Base IP
        - Represents an IP contained in the range



link util: https://www.ipaddressguide.com/cidr 

Public vc. Private IP (IPv4)

    - The Internet Assigned Numbers Authority (IANA) established certain blocks of IPV4 addresses for the use of private (LAN) and public (Internet) address.