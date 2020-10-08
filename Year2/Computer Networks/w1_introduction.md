# Computer Networks Introduction

A computer network is a set of nodes/end devices connected by a communication link.  

A node can be computer, printer, mobile phone or any other devices capable of sending/receiving data in the network. 

Communication link can be a wired link or wireless link that carries the data. 

## Network Interface Controller
Network Interface Controller: A network interface controller is a computer hardware component that connects a computer to a computer network.

## Network Topology - Direct Connectivity
Point-to-Point Connection 

Direct Connection of N users such as  Bus, Mesh…

Problem: Point-to-Point connects only two users
* Mesh : Inefficient w.r.t number of links
* Bus: Inefficient w.r.t bandwidth usage

## Network Topology - Indirect Connectivity
Star: One-hop path to any node
Ring

Star and Ring topologies require sophisticated switching, filtering and forwarding functionalities

Problem: Single Point Failure Scalability

## Network Topology - Hybrid Connectivity
A hybrid topology is the combination of the above topologies.
A common hybrid is a star bus: several star-wired networks are interconnected via a bus.

* Useful where groups of workstations are required to be connected to other more distant groups of workstations.


Problem: Problems of star and bus topologies

## Inter-Network - Internet
Inter-Network - Network of Networks organized hierarchically.
Typical Inter-Network consists of the following  Hierarchy based on the size of the networks
* Local Area Network (LAN) -  Geographically limited to networks extending up to less than a Kilometre **Ex:** Campus Network, Corporate Network etc.,
* Metropolitan Area Network (MAN) – Geographically limited to network within a city or a metropolitan area
* Wide Area Network (WAN) – Connects large networks of various types spread across a large geographical region 


## Inter-Connectivity Devices: Hub
* Message sent by one node is sent to all other nodes
* Physical layer devices
* Wasted Bandwidth
* Increase Security Risk
* One Collision Domain
* Half-duplex
* Local Network

## Inter-Connecting Devices: Bridge
* Message processed based on MAC/hardware addresses
* Data-link layer devices
* Bridge is not a practical device for end host
* Connect Two LAN segments
* Only two ports

## Inter-Connecting Devices: Switch
* Switch is a bridge with more than two ports. 
* Overcome the limitation of hub and bridge
* Message processed based on MAC address
* Data-link layer devices
* Full-duplex operation

| Port | Devices  | Mac Address               |
| ---- | -------  | --------------------------|
| A    | Detected | HH:HH:HH:HH:HH:HH (Hub 1) |
| B    | Detected | EE:EE:EE:EE:EE:HEE        |
| C    | Detected | HH:HH:HH:HH:HH:HH (Hub 2) |
| D    | Detected | FF:FF:FF:FF:FF:FF         |

Hub, Bridge and Switch are network devices use to connect devices on same network

## Inter-Connecting Devices: Router
Router operates on network layer

Router is used to connect local devices to outer world such as internet

When a packet arrive at router, based on destination address, router calculate the best possible path using routing table.

Router is a common type of gateway.

## Inter-Connecitng Devices: Gateways
Gateways are routers with capability to protocol translation

Term “Default Gateway”


### Links
https://www.youtube.com/watch?v=a9SJG4qzRv4&list=PLTFCpqU24Ce5WTqzBgODxmawNs5mSc2m7&ab_channel=InstructorAlton

https://www.geeksforgeeks.org/network-devices-hub-repeater-bridge-switch-router-gateways/








