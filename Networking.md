## What is Networking?
Networking refers to the process of connecting computers, servers, and other devices together to share resources and communicate with each other. It enables devices to exchange data and provides a platform for applications and services to operate across multiple devices.
                                 Or
A network is a connection between computing devices that are connected in various ways in order to communicate and share information or resources.

---

## Models in Networking

### 1. OSI Model (Open Systems Interconnection Model)
A conceptual framework that standardizes how different computer systems communicate over a network. It consists of **7 layers**:
1. **Physical Layer**: Deals with hardware transmission.
2. **Data Link Layer**: Manages data frames between devices.
3. **Network Layer**: Handles routing of data packets.
4. **Transport Layer**: Ensures end-to-end communication.
5. **Session Layer**: Manages sessions between devices.
6. **Presentation Layer**: Translates data formats.
7. **Application Layer**: Provides user services like email and file transfer.

### 2. TCP/IP Model (Transmission Control Protocol/Internet Protocol Model)
A more practical model, often used as the basis for the internet. It consists of **4 layers**:
1. **Network Interface Layer**: Corresponds to OSI's physical and data link layers.
2. **Internet Layer**: Handles IP addressing and routing.
3. **Transport Layer**: Manages end-to-end communication and data integrity (TCP/UDP).
4. **Application Layer**: Manages high-level communication, e.g., HTTP, FTP.

---

## Servers and Types of Servers

### What is a Server?
A server is a powerful computer or device that provides services or resources to other computers (clients) on the network. Servers manage data, resources, and services for multiple clients simultaneously.

### Types of Servers:
1. **File Server**: Stores and manages files for network clients.
2. **Web Server**: Hosts websites and serves web pages to users over the internet.
3. **Database Server**: Provides database services and manages database-related queries.
4. **Mail Server**: Manages and facilitates email services for users.
5. **DNS Server**: Resolves domain names to IP addresses for network communication.
6. **Proxy Server**: Acts as an intermediary between a client and the server for security and caching.
7. **Game Server**: Hosts multiplayer online games and manages game-related data and player interactions.

---

## Types of Networks

1. **LAN (Local Area Network)**:
   - Covers a small geographical area (e.g., within a building or campus).
   - High data transfer rates and low latency.
   - Typically connected using Ethernet cables or Wi-Fi.

2. **WAN (Wide Area Network)**:
   - Covers a large geographical area (e.g., between cities, countries).
   - Slower data transfer rates compared to LAN, but allows for long-distance communication.
   - The internet is the largest example of a WAN.

3. **MAN (Metropolitan Area Network)**:
   - Covers a city or metropolitan area.
   - Typically used for connecting multiple LANs in a city.
   - Provides a middle-ground between LAN and WAN in terms of data speed and range.

4. **PAN (Personal Area Network)**:
   - A small network for personal devices, typically within a range of a few meters.
   - Examples: Bluetooth, Wi-Fi for personal devices.

5. **VPN (Virtual Private Network)**:
   - A secure, encrypted connection over the internet that allows remote users or offices to connect to a private network.
   - Provides privacy and security when accessing data over untrusted networks like public Wi-Fi.

---

## Types of Network Topologies

1. **Bus Topology**:
   - A single central cable (bus) connects all devices.
   - Cheap and easy to install but prone to network failure if the central bus fails.

2. **Star Topology**:
   - All devices are connected to a central device (hub or switch).
   - Highly reliable; if one device fails, it doesn't affect others, but if the central device fails, the whole network is affected.

3. **Ring Topology**:
   - Devices are connected in a circular fashion.
   - Data travels in one direction, passing through each device until it reaches the destination.
   - Can be slow due to the need for data to travel through every device.

4. **Mesh Topology**:
   - Every device is connected to every other device.
   - Provides high redundancy and reliability, as there are multiple paths for data to travel.
   - Expensive and complex to install.

5. **Tree Topology**:
   - Combines characteristics of bus and star topologies.
   - Devices are grouped in a hierarchical structure, with central nodes connecting to higher nodes.
   - Allows for scalability but may suffer if the central node fails.

6. **Hybrid Topology**:
   - A combination of two or more topologies.
   - Designed to meet specific network requirements for scalability, reliability, and performance.

---
# Networking Devices

---

## 1. Hub

### Definition:
A **Hub** is a basic networking device that connects multiple devices in a Local Area Network (LAN). It operates at the **OSI Layer 1 (Physical Layer)** and broadcasts data to all devices connected to it, without any filtering or routing.

### Key Features:
- **Broadcasts data** to all devices connected, regardless of the destination.
- No **intelligence** in directing traffic, resulting in network congestion.
- Typically used in **small networks** or **home setups**.

### Types:
- **Passive Hub**: Simply transmits data without any amplification.
- **Active Hub**: Amplifies and retransmits data to extend network range.

### Limitations:
- **Bandwidth sharing**: All devices share the same bandwidth.
- **Security risks**: Data is sent to all devices, exposing sensitive information.

---

## 2. Repeater

### Definition:
A **Repeater** is a device used to extend the range of a network by amplifying and retransmitting signals. It works at the **OSI Layer 1 (Physical Layer)**.

### Key Features:
- **Signal amplification**: Repeats the data signal to cover longer distances.
- Primarily used for **long-distance communication** between two network segments.

### Use Cases:
- Extends the distance of a wired network (Ethernet).
- Commonly used in **fiber optics** and **wireless communication**.

### Limitations:
- **No data processing**: It just amplifies the signal without modifying it.

---

## 3. Modem

### Definition:
A **Modem** (Modulator-Demodulator) is a device that converts digital data from a computer into analog signals for transmission over phone lines or vice versa.

### Key Features:
- **Modulation**: Converts digital signals into analog signals.
- **Demodulation**: Converts incoming analog signals back to digital.
- Primarily used for **internet access** over telephone lines or cable connections.

### Types:
- **Dial-up Modem**: Converts data to and from analog signals for dial-up internet.
- **DSL Modem**: Used for high-speed internet over telephone lines.
- **Cable Modem**: Used for broadband internet over cable lines.

### Limitations:
- **Limited speed** compared to modern internet connections (fiber, wireless).
- **Subject to interference** on analog lines.

---

## 4. NIC (Network Interface Card)

### Definition:
A **Network Interface Card (NIC)** is a hardware component that allows a device (such as a computer or server) to connect to a network. It operates at the **OSI Layer 2 (Data Link Layer)** and is responsible for establishing a physical link with the network.

### Key Features:
- Provides a **physical connection** to a network via wired or wireless mediums (Ethernet, Wi-Fi).
- **MAC Address**: Every NIC has a unique Media Access Control (MAC) address used for identifying the device on the network.
- Supports both **wired (Ethernet)** and **wireless (Wi-Fi)** network types.

### Types:
- **Wired NIC**: Typically uses **Ethernet** cables to connect to the network.
- **Wireless NIC (Wi-Fi Adapter)**: Allows a device to connect to the network wirelessly.

### Limitations:
- **Physical Limitations**: Wired NICs require a physical cable connection, while wireless NICs may face signal interference.
- **Speed limitations**: Can vary based on the type of network and the NIC's specifications.

---

## 5. Switch

### Definition:
A **Switch** is a networking device that operates at the **OSI Layer 2 (Data Link Layer)** and is used to connect multiple devices within a LAN. Unlike hubs, switches can **filter traffic** and **forward data** only to the intended destination.

### Key Features:
- **MAC Address Table**: Switch uses MAC addresses to forward data to the correct device.
- Reduces **collisions** compared to hubs by providing dedicated channels for communication.
- More **efficient** and secure than hubs.

### Types:
- **Unmanaged Switch**: Plug-and-play, with no configuration required.
- **Managed Switch**: Allows configuration and monitoring, often used in large networks.

### Limitations:
- Does not work well across different network segments (requires a router).

---

## 6. Bridge

### Definition:
A **Bridge** is a networking device that operates at the **OSI Layer 2 (Data Link Layer)** and is used to connect two or more separate network segments, allowing them to function as a single network.

### Key Features:
- **Traffic Filtering**: Bridges filter traffic between network segments based on MAC addresses.
- **Collision Domain Reduction**: Helps in reducing network traffic collisions by creating smaller collision domains.
- **Works** in **LAN environments**.

### Types:
- **Transparent Bridge**: Operates without changing the format of data being transmitted.
- **Source Routing Bridge**: Uses source routing to determine the best path for data transmission.

---

## 7. Router

### Definition:
A **Router** is a device that operates at the **OSI Layer 3 (Network Layer)** and is used to connect multiple networks, typically LANs and WANs. It forwards data packets between networks based on IP addresses.

### Key Features:
- **Routing Table**: Routers maintain routing tables to determine the best path for data.
- **Network Address Translation (NAT)**: Routers commonly perform NAT to allow multiple devices on a local network to share a single public IP address.
- **Inter-network Communication**: Facilitates communication between different networks, including between home and the internet.

### Types:
- **Static Router**: Uses manually configured routes.
- **Dynamic Router**: Uses routing protocols (like OSPF, BGP) to automatically determine the best path.

### Limitations:
- **Latency**: Can introduce latency due to the routing process.
- **Configuration Complexity**: May require configuration and management, especially in larger networks.

---

## 8. Gateway

### Definition:
A **Gateway** is a build in software in routers that connects two different types of networks, typically a local network and a wide-area network (WAN) or different protocols (e.g., IP to non-IP). It operates at the **OSI Layer 3 (Network Layer)** or higher.

### Key Features:
- **Protocol Translation**: Converts data between different protocols.
- Commonly used to connect different network architectures, such as **connecting a LAN to the internet**.
- **Data Routing**: It routes data based on the specific needs of the communication.

### Use Cases:
- **VoIP Gateways**: Converts digital phone signals into traditional telephone network signals.
- **Web Gateways**: Facilitates web browsing between different network systems.

---

## 9. Wireless Access Point (WAP)

### Definition:
A **Wireless Access Point (WAP)** is a device that allows wireless devices (like laptops, smartphones) to connect to a wired network via Wi-Fi. It operates at the **OSI Layer 2 (Data Link Layer)**.

### Key Features:
- **Wi-Fi Connectivity**: Provides Wi-Fi connections for devices to access a wired network.
- **Extends Coverage**: Used to extend the wireless coverage of an existing network.
- Can be integrated with **routers** or work as standalone devices in a network.

### Types:
- **Standalone WAP**: Independent device that provides wireless connectivity.
- **Integrated WAP**: Part of a router or switch that provides wireless connectivity.

### Limitations:
- **Signal Interference**: Can be affected by physical obstacles and other devices emitting signals on the same frequency.
- **Limited Range**: Coverage area may be limited compared to wired connections.

---
## Internet

The internet is essentially a connection of **Wide Area Networks (WANs)** that spans across the globe, connecting millions of devices.

---

## Identifying Devices on a Network

### IP Address

An **IP Address** (Internet Protocol Address) is used to identify a host on a network. It is typically divided into **four octets**. Each octet represents part of the address and is calculated through a technique known as **IP addressing & subnetting**. An IP address can either be **public** or **private**, depending on the network type.

---

### Media Access Control (MAC) Address

A **MAC Address** is similar to a **serial number** and identifies a network device at the hardware level. It is a **12-character hexadecimal** number (e.g., `a4:c3:f0:85:ac:2d`). The first six characters represent the company that manufactured the network device, and the last six represent a unique number assigned to the device.

---

## IPv4 vs. IPv6

### IPv4 (Internet Protocol Version 4)

IPv4 is the **fourth version** of the Internet Protocol and is still widely used for identifying devices on a network.

#### Key Features of IPv4:
- **Address Format:** 32-bit address (e.g., `192.168.1.1`).
- **Address Space:** Supports around **4.3 billion** unique addresses.
- **Header Size:** 20 bytes (minimum).
- **Configuration:** Can be configured manually or using **DHCP**.
- **Security:** Relies on external protocols like **IPsec** for security.
  
Example IP: `192.168.0.1`

---

### IPv6 (Internet Protocol Version 6)

IPv6 is the successor to IPv4 and provides a much larger address space and improved features.

#### Key Features of IPv6:
- **Address Format:** 128-bit address (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
- **Address Space:** Supports approximately **\(3.4 \times 10^{38}\)** unique addresses.
- **Header Size:** 40 bytes.
- **Configuration:** Supports **auto-configuration**.
- **Security:** Built-in support for encryption (e.g., **IPsec** is mandatory).

Example IP: `2001:0db8:85a3::8a2e:0370:7334`

---

## Key Differences Between IPv4 and IPv6

| Feature               | IPv4                            | IPv6                             |
|-----------------------|---------------------------------|-----------------------------------|
| **Address Size**       | 32-bit                          | 128-bit                          |
| **Address Notation**   | Dotted decimal (e.g., `192.168.1.1`) | Hexadecimal (e.g., `2001:db8::1`) |
| **Address Space**      | 4.3 billion addresses           | Virtually unlimited              |
| **Header Size**        | 20 bytes                        | 40 bytes                         |
| **Security**           | Optional (IPsec)                | Mandatory (IPsec)                |
| **Configuration**      | Manual/DHCP                     | Auto-configuration supported     |
| **Fragmentation**      | Routers and hosts               | Hosts only                       |

---

## MAC Address

A **MAC Address** is a unique identifier for a network device. It is represented as a 12-character hexadecimal number (e.g., `a4:c3:f0:85:ac:2d`). The first six characters represent the manufacturer, while the last six are a unique identifier for the device.

---

## MAC Address Spoofing

**MAC Address spoofing** is when a network device pretends to be another device by changing its MAC address. This can break poorly designed security systems that trust devices based solely on MAC addresses. 

**Example Scenario:**
If a firewall is configured to allow communication from a specific MAC address (e.g., the administrator’s MAC), an attacker can "spoof" this MAC address, and the firewall would mistakenly trust the communication as coming from the administrator.

---

## Ping

**Ping** is a simple tool used to test the reliability and existence of a network connection. It uses **ICMP** (Internet Control Message Protocol) packets to check the performance and availability of devices in a network.

---

# Physical Layer

The **Physical Layer** is the first and lowest layer of the **OSI Model**, responsible for the physical connection between devices. It defines the hardware and transmission medium used to transmit raw data (bits) across the network.

## Key Responsibilities of the Physical Layer:
1. **Data Transmission:** Converts digital data into electrical, optical, or radio signals for transmission.
2. **Bit Synchronization:** Ensures data is sent and received at the correct timing.
3. **Physical Topology:** Defines how devices are physically connected (e.g., bus, star, ring topologies).
4. **Transmission Medium:** Determines the medium over which data is transmitted, such as cables or wireless signals.

---

# Transmission Media

Transmission media refers to the physical path used to carry signals from one device to another in a network. It is broadly classified into two types:

1. **Guided Media:** The signal travels through a physical medium, such as cables.
2. **Unguided Media:** The signal is transmitted wirelessly through air or space.

---

## Types of Transmission Media

### 1. **Guided Media**
Guided media uses cables or physical mediums to transmit signals. Common types include:

#### (a) **Twisted Pair Cable**
- **Description:** Two insulated copper wires twisted together to reduce electromagnetic interference.
- **Types:**
  - **Unshielded Twisted Pair (UTP):** Most common for Ethernet cables.
  - **Shielded Twisted Pair (STP):** Contains an additional shielding layer for better noise resistance.
- **Advantages:**
  - Cost-effective and easy to install.
  - Suitable for short-distance communication.
- **Disadvantages:**
  - Limited bandwidth and prone to interference.
- **Common Use Cases:** LANs, telephone lines.

---

### UTP Categories

| **UTP Category** | **Data Rate**             | **Max Length** | **Cable Type**          | **Application**                  |
|-------------------|---------------------------|----------------|-------------------------|----------------------------------|
| **Cat 1**         | Up to 1 Mbps             | 100 meters     | Voice-grade             | Analog voice (telephone lines)  |
| **Cat 2**         | Up to 4 Mbps             | 100 meters     | Low-speed               | Token Ring networks             |
| **Cat 3**         | Up to 10 Mbps            | 100 meters     | Data-grade              | Ethernet (10BASE-T), voice      |
| **Cat 4**         | Up to 16 Mbps            | 100 meters     | Improved data-grade     | Token Ring networks             |
| **Cat 5**         | Up to 100 Mbps           | 100 meters     | High-speed data-grade   | Ethernet (100BASE-TX)           |
| **Cat 5e**        | Up to 1 Gbps             | 100 meters     | Enhanced data-grade     | Gigabit Ethernet, LANs          |
| **Cat 6**         | Up to 10 Gbps (short distances) | 100 meters | High-performance data-grade | High-speed LANs, data centers  |
| **Cat 6a**        | Up to 10 Gbps            | 100 meters     | Augmented data-grade    | High-speed networks             |
| **Cat 7**         | Up to 10 Gbps            | 100 meters     | Shielded, high-performance | Data centers, enterprise networks |
| **Cat 8**         | Up to 40 Gbps            | 30 meters      | Shielded, ultra-high performance | Data centers, server-to-server |

---

#### (b) **Coaxial Cable**
- **Description:** A single copper core surrounded by an insulating layer, metallic shielding, and an outer plastic cover.
- **Advantages:**
  - Better resistance to interference than twisted pair cables.
  - Can carry signals over longer distances.
- **Disadvantages:**
  - Bulkier and more expensive than twisted pair cables.
- **Common Use Cases:** Cable TV, internet connections, and high-frequency transmission.

---

#### (c) **Fiber Optic Cable**
- **Description:** Uses light signals to transmit data through a glass or plastic core.
- **Advantages:**
  - High-speed data transmission and extremely low signal loss.
  - Immune to electromagnetic interference.
  - Can transmit over very long distances.
- **Disadvantages:**
  - Expensive and difficult to install.
- **Common Use Cases:** Backbone networks, long-distance communication, and high-bandwidth applications.

---

### Fiber Optic Cable Types

| **Fiber Type**       | **Core Diameter** | **Distance**          | **Speed**              | **Applications**               |
|-----------------------|-------------------|------------------------|------------------------|---------------------------------|
| **Single-Mode Fiber** | 8-10 microns      | Up to 80-100 km        | 10 Gbps to 100 Gbps    | Long-distance communication, WANs |
| **Multi-Mode Fiber**  | 50-62.5 microns   | Up to 2 km            | 1 Gbps to 10 Gbps      | Short-distance communication, LANs |
| **Plastic Optical Fiber (POF)** | 1 mm             | Up to 100 meters      | Up to 1 Gbps          | Home networks, consumer electronics |


---

### 2. **Unguided Media**
Unguided media transmits data wirelessly through electromagnetic waves. Common types include:

#### (a) **Radio Waves**
- **Advantages:** Long-range and omnidirectional.
- **Use Cases:** AM/FM radio, Wi-Fi.

#### (b) **Microwaves**
- **Advantages:** High bandwidth and directional.
- **Use Cases:** Satellite communication, cellular networks.

#### (c) **Infrared (IR)**
- **Advantages:** Simple and inexpensive.
- **Use Cases:** Remote controls, short-range communication.

#### (d) **Satellite Communication**
- **Advantages:** Global coverage.
- **Use Cases:** GPS, satellite TV, internet in remote areas.

---

# Comparison of Cable Types

| **Feature**          | **Twisted Pair**      | **Coaxial Cable**   | **Fiber Optic**       |
|-----------------------|-----------------------|---------------------|-----------------------|
| **Cost**              | Low                  | Moderate            | High                  |
| **Speed**             | Moderate             | Moderate            | Very High             |
| **Distance**          | Short                | Moderate            | Long                  |
| **Interference**      | High (UTP), Moderate (STP) | Low           | None                  |
| **Use Cases**         | LANs, telephones     | Cable TV, internet  | Backbone, long-distance |

---
