# 🌐 Internet Networking CA-1 – Office Network Infrastructure Design

![Networking](https://img.shields.io/badge/Networking-Infrastructure-blue?style=for-the-badge)
![Topology](https://img.shields.io/badge/Network-Topology-green?style=for-the-badge)
![Routing](https://img.shields.io/badge/Routing-Static%20Routing-orange?style=for-the-badge)
![IPv4](https://img.shields.io/badge/IP-IPv4-red?style=for-the-badge)

This project presents the **design and implementation of a network infrastructure for an eight-floor office building**. The objective is to ensure **efficient communication, scalability, and fault tolerance** across all floors using a structured network design.

The system uses a **hybrid network topology**, **static routing**, and a well-defined **IP addressing scheme** to maintain reliable communication between all network segments.

---

# 📌 Table of Contents

- Introduction  
- Network Architecture  
- Network Topology  
- IP Addressing Scheme  
- Routing Strategy  
- Connectivity Testing  
- Project Components  
- Future Enhancements  
- Author  
- License  

---

# 📖 Introduction

Modern office environments require **reliable and scalable network infrastructures** to support communication, data sharing, and system connectivity across multiple floors.

This project focuses on designing a structured **eight-floor office network** that ensures:

- Efficient data communication  
- Fault tolerance  
- Scalability for future expansion  
- Organized IP addressing and routing

The design integrates **multiple network topologies** to optimize both **performance and reliability**.

---

# 🏢 Network Architecture

The office building consists of **eight floors**, each with multiple workstations connected through switches and routers.

Key components of the network include:

- Computers / Workstations
- Network Switches
- Routers
- Structured IP Addressing
- Static Routing Configuration

Each floor has its own **local area network (LAN)**, and routers enable communication between different floors.

---

# 🔗 Network Topology

The network uses a **hybrid topology** combining multiple network structures for optimal performance.

### Floors 1–3: Star Topology
- Six computers per floor
- All systems connect to a **central switch**
- Easy troubleshooting and device management

### Floors 4–5: Ring Topology
- Computers connected in a circular data path
- Ensures continuous data flow and redundancy

### Floors 6–8: Mesh Topology
- Multiple interconnections between devices
- Provides **maximum fault tolerance**
- Ensures alternative communication paths

### Router Connectivity
All routers are connected using a **Bus Topology**, allowing communication between floors through a shared backbone network.

---

# 🌍 IP Addressing Scheme

A structured **IPv4 addressing plan** is implemented to ensure organized communication.

### Floors 1–3
- Uses **Class C private IPv4 addresses**
- Intended for internal LAN communication

### Floors 4–8
- Uses **Class A public IPv4 addresses**
- Allows broader connectivity and routing flexibility

### Router-to-Router Communication
- Uses **Class A public IPv4 addressing**
- Maintains a consistent routing framework across the network

---

# 🔀 Routing Strategy

The network implements **Static Routing** to manage communication between floors.

Key characteristics:

- Manually configured routing tables
- Predictable and controlled network traffic
- Reduced routing overhead
- Improved network stability

Static routes ensure that data packets follow predefined paths between the different LANs.

---

# 📡 Connectivity Testing

Network connectivity was validated using **ping tests** between devices on different floors.

Results confirmed:

- Successful **inter-LAN communication**
- Proper routing configuration
- No packet loss during testing
- Reliable communication between network segments

This verifies the **efficiency and correctness of the network design**.

---

# 📂 Project Components

The project includes:

- **Network Topology Diagram**  
  Visual representation of the office network infrastructure.

- **Router and Switch Configuration**  
  Static routing and interface configurations.

- **Network Design Documentation**  
  Detailed explanation of topology, addressing, and routing.

---

# 🚀 Future Enhancements

Potential improvements for the network include:

- Implementing **VLAN segmentation** for enhanced security and traffic management
- Adding **load balancing mechanisms** for better network performance
- Implementing **failover routing strategies** for improved fault tolerance
- Expanding the infrastructure to support **wireless networking**
- Integrating **network monitoring systems**

---

# 👤 Author

**Ayushman Behera**

🎓 B.Tech – Computer Science & Engineering (Data Science)  
🏫 Lovely Professional University  

🔗 GitHub: https://github.com/ayubeh1513  
📧 Email: ayushmanbehera689@gmail.com

---

# 📄 License

This project is licensed under the **MIT License**.
