# Topologies

## Bus Topology

Bus Topology is a type in which the systems are connected in a single cable . It is a less complex topology mainly used in labs,schools etc..

```mermaid
flowchart LR
    B1((" ")) --- B2((" "))
    B2 --- B3((" "))
    B3 --- B4((" "))
    B4 --- B5((" "))
    PC1["PC 1"] --- B1
    PC2["PC 2"] --- B2
    PC3["PC 3"] --- B3
    PC4["PC 4"] --- B4
    PC5["PC 5"] --- B5

```

## Star Topology

Star Topology is a network setup in which each device is connected to a central node called a hub. The hub manages the data flow between the devices. If one device wants to send data to another device, it has to first send the information to the hub, and then the hub transmits that data to the required device.


```mermaid
     graph TD
    H[Hub/Switch]
    
    H --- N1[Node 1]
    H --- N2[Node 2]
    H --- N3[Node 3]
    H --- N4[Node 4]
    H --- N5[Node 5]
    H --- N6[Node 6]
    H --- N7[Node 7]
    H --- N8[Node 8]

```    

## Mesh Topology

In mesh topology every computer in the network is connected to each other. It is a bit expensive so much wires are need to be used. If you want to add a new computer to the network you need to to connect it with all other systems in the network 


```mermaid
graph TD
   
        N1(Node 1) --- N2(Node 2)
        N1 --- N3(Node 3)
        N1 --- N4(Node 4)
        
        N2 --- N3
        N2 --- N4
        
        N3 --- N4
    end

    
```
    
  