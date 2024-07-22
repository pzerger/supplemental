# Network Architecture

Additional reading on some network architecture topics on the CompTIA Network+ exam.

# Table of Contents

- [3-Tier Network Architecture](#3-tier-network-architecture)
- [Spine and Leaf Network Architecture](#spine-and-leaf-network-architecture)

## 3-Tier Network Architecture

The 3-tier network architecture is a hierarchical design that divides the network into three distinct layers: access, distribution, and core. This architecture provides a scalable, resilient, and efficient framework for managing network traffic and resources.

### 3-Tier Network Architecture: Access

The access layer, also known as the edge layer, is the lowest tier in the 3-tier architecture. It is responsible for connecting end devices, such as computers, printers, and IP phones, to the network. Access layer switches provide port security, VLANs, and Quality of Service (QoS) to manage and prioritize traffic. This layer focuses on providing access to network resources and enforcing security policies.

### 3-Tier Network Architecture: Core

The core layer is the highest tier in the 3-tier architecture. It is responsible for providing high-speed backbone connectivity between distribution layer devices. Core layer switches and routers are designed for high performance, low latency, and redundancy. This layer focuses on fast and reliable transport of data across the network, without the need for complex packet manipulation or access control.

### 3-Tier Network Architecture: Distribution

The distribution layer, also known as the aggregation layer, is the middle tier in the 3-tier architecture. It is responsible for aggregating traffic from the access layer and routing it to the core layer. Distribution layer switches and routers provide routing, filtering, and QoS functions. This layer also serves as a boundary between the access and core layers, enforcing security policies and access control.

[Back to ToC](#table-of-contents)

## Spine and Leaf Network Architecture

The spine and leaf network architecture is a two-tier design that provides high bandwidth, low latency, and scalability for data center networks. This architecture consists of spine switches and leaf switches, which are interconnected in a full-mesh topology.

### Spine and Leaf Network Architecture: Leaf switches

Leaf switches, also known as top-of-rack (ToR) switches, are located in the server racks and connect directly to the servers. Each leaf switch is connected to every spine switch in the network, creating a full-mesh topology. Leaf switches are responsible for providing access to the servers and enforcing access control policies.

### Spine and Leaf Network Architecture: Redundancy

The spine and leaf architecture provides high redundancy by connecting each leaf switch to every spine switch. This full-mesh topology ensures that there are multiple paths available between any two devices in the network. If a spine switch fails, traffic can still be routed through the remaining spine switches, maintaining network connectivity.

### Spine and Leaf Network Architecture: Scalability

The spine and leaf architecture is highly scalable, as it allows for the addition of new leaf switches and servers without requiring changes to the existing network topology. As the number of servers grows, new leaf switches can be added to the network, and each new leaf switch is connected to every spine switch. This modular design allows for easy expansion and scalability.

### Spine and Leaf Network Architecture: Spine switches

Spine switches form the backbone of the spine and leaf architecture. They are responsible for routing traffic between leaf switches and providing high-speed connectivity. Spine switches do not connect directly to servers; instead, they connect to all the leaf switches in the network. This design allows for a simple and efficient routing architecture, as each spine switch maintains a routing table for all the leaf switches.

### Spine and Leaf Network Architecture: Top of rack (ToR)

Top of rack (ToR) switches, also known as leaf switches, are located in the server racks and connect directly to the servers. Each ToR switch is connected to every spine switch in the network, creating a full-mesh topology. ToR switches are responsible for providing access to the servers and enforcing access control policies. By locating the switches close to the servers, the spine and leaf architecture minimizes the cable length and latency between the servers and the network.

[Back to ToC](#table-of-contents)