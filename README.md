# Internet Networking CA-1

## Overview
This project outlines the **network infrastructure** for an **eight-floor office building**, ensuring efficient communication, scalability, and fault tolerance. The network is designed using a hybrid topology approach, static routing for inter-floor communication, and a structured **IP addressing scheme**.

## Network Topology
The office network follows a **hybrid topology model** to optimize performance and reliability:
- **Floors 1-3:** Star topology, where six computers per floor connect to a central switch for easy management.
- **Floors 4-5:** Ring topology, ensuring smooth data flow and redundancy.
- **Floors 6-8:** Mesh topology, providing maximum fault tolerance with multiple interconnections.
- **Router Connectivity:** All routers are connected using a **bus topology** for seamless inter-floor communication.

## IP Addressing Scheme
- **Floors 1-3:** Class C private IPv4 addresses for internal communication.
- **Floors 4-8:** Class A public IPv4 addresses for broader connectivity.
- **Router-to-Router Communication:** Uses Class A public IPv4 addresses to maintain a consistent routing framework.

## Routing Strategy
- **Static Routing** is implemented for inter-floor communication to ensure stability and avoid unnecessary routing changes.
- Predefined routes facilitate controlled and predictable data flow between floors.

## Connectivity Testing
- Successful **ping tests** were conducted between all floors to verify inter-LAN communication.
- The tests confirm that packets reach their destinations without loss, ensuring **network efficiency and reliability**.

## Project Files
- **Network Diagram:** Full topology representation of the office network (see `FULL.png`).
- **Configuration Scripts:** Router and switch configurations for static routing (to be added if required).

## Future Enhancements
- Implementing **VLAN segmentation** for additional security and traffic management.
- Introducing **load balancing and failover strategies** to enhance network resilience.
- Expanding to support **wireless connectivity** for additional device access.

## Contributors
- **[Your Name]** – Network Architecture & Design

For any issues or contributions, feel free to open a pull request or raise an issue.
