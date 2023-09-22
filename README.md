# Github Repo Automation-Project C&I

## Wat gaan we nodig hebben?
- Routers (van PNET)
    - 2 poorten
        - 1 poort voor WAN
        - 1 poort voor LAN 
- Ubuntu client
    - Ansible
    - VSCode
    - SSH connection naar routers

<br>

## De Routers:

|Naam|Port|Ip|Subnet|WAN/LAN|
|---|---|---|---|---|
|R1|GI0/1|192.168.10.1|/24|LAN|
||GI0/2|DHCP|/24|WAN|
|R2|GI0/1|192.168.20.1|/24|LAN|
||GI0/2|DHCP|/24|WAN|
|R3|GI0/1|192.168.30.1|/24|LAN|
||GI0/2|DHCP|/24|WAN|

<br>

- Pueriles
- From https://github.com/Frusti007
