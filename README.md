## ex01 

```
flowchart LR
    classDef host fill:#616a6b,stroke:#95a5a6,color:#fff

    subgraph LinkA["Link A - 192.168.1.0/24"]
        PC0["PC0<br/>192.168.1.3"]:::host
        PC1["PC1<br/>192.168.1.4"]:::host
    end

    subgraph LinkB["Link B - 192.168.13.80/29"]
        PC2["PC2<br/>192.168.13.81"]:::host
        PC3["PC3<br/>192.168.13.82"]:::host
    end

    subgraph LinkC["Link C - 192.168.13.240/28"]
        PC4["PC4<br/>192.168.13.254"]:::host
        PC5["PC5<br/>192.168.13.253"]:::host
    end

    PC0 ---|"FastEthernet0 -- FastEthernet0"| PC1
    PC2 ---|"FastEthernet0 -- FastEthernet0"| PC3
    PC4 ---|"FastEthernet0 -- FastEthernet0"| PC5

```

pc 0 :
# IP Address : 192.168.1.3
# Subnet Mask: 255.255.255.0
pc 1 :
# IP Address : 192.168.1.4
# Subnet Mask: 255.255.255.0
pc 2:
# IP Address : 192.168.13.81
# Subnet Mask: 255.255.255.248
pc3:
# IP Address : 192.168.13.82
# Subnet Mask: 255.255.255.248
pc4:
# IP Address : 192.168.13.254
# Subnet Mask: 255.255.255.240
pc5 :
# IP Address : 192.168.13.253
# Subnet Mask: 255.255.255.240



| Link | Subnet | Hosts |
|---|---|---|
| PC0–PC1 | 192.168.1.0/24 | .3, .4 |
| PC2–PC3 | 192.168.13.80/29 | .81, .82 |
| PC4–PC5 | 192.168.13.240/28 | .253, .254 |

