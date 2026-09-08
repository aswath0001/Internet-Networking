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
    %% Central node (Switch/Hub)
    S[Switch]:::center

    %% Connected devices
    PC1[PC 1]:::device
    PC2[PC 2]:::device
    PC3[PC 3]:::device
    PC4[PC 4]:::device
    PC5[PC 5]:::device

    %% Connections (Star topology: all connect to center)
    S --- PC1
    S --- PC2
    S --- PC3
    S --- PC4
    S --- PC5

    %% Styles
    classDef center fill:#ffcc00,stroke:#333,stroke-width:2px;
    classDef device fill:#99ccff,stroke:#333,stroke-width:1px;
```