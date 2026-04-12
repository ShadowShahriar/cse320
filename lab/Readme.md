## Lab Examination

### Experiments List

1. [**Network Cabling &#124; Straight Through and Crossover Cable Connection using RJ45 Connector**](https://shadowshahriar.github.io/cse320/lab/2026-01-19/report.pdf)
2. [**HTTP Web Server Accessing with DNS and FTP Server**](https://shadowshahriar.github.io/cse320/lab/2026-01-26/report.pdf)
3. [**VLAN Configuration**](https://shadowshahriar.github.io/cse320/lab/2026-02-02/report.pdf)
4. [**Static Routing**](https://shadowshahriar.github.io/cse320/lab/2026-02-09/report.pdf)
5. [**RIP Routing Protocol**](https://shadowshahriar.github.io/cse320/lab/2026-03-30/report.pdf)
6. [**Wireless Routing**](https://shadowshahriar.github.io/cse320/lab/2026-04-06/report.pdf)

---

### Full Forms

| Abbreviation  | Full Form                               |
| :------------ | :-------------------------------------- |
| DNS           | Domain Name System                      |
| HTTP          | Hypertext Transfer Protocol             |
| HTTPS         | Hypertext Transfer Protocol Secure      |
| FTP           | File Transfer Protocol                  |
| IP (IPv4)     | Internet Protocol (version 4)           |
| VLAN          | Virtual Local Area Network              |
| RIP           | Routing Information Protocol            |
| DHCP          | Dynamic Host Configuration Protocol     |
| ICMP          | Internet Control Message Protocol       |
| MANET         | Mobile Ad-hoc Networking                |
| WSN           | Wireless Sensor Network                 |
| RJ-45         | Registered Jack-45                      |
| UTP           | Unshielded Twisted Pair                 |
| EMI           | Electromagnetic Interference            |
| TIA           | Telecommunications Industry Association |
| EIA           | Electronic Industries Alliance          |
| LAN           | Local Area Network                      |
| TX            | Transmit (Pair)                         |
| RX            | Receive (Pair)                          |
| NIM           | Network Interface Module                |
| Fa            | FastEthernet                            |
| Gi            | GigabitEthernet                         |
| CLI           | Command Line Interface                  |
| GUI           | Graphical User Interface                |
| SSID          | Service Set Identifier                  |
| WPA2-Personal | Wi-Fi Protected Access 2                |
| AES           | Advanced Encryption Standard            |
| PSK           | Pre-Shared Key (implied by WPA2-PSK)    |
| URL           | Uniform Resource Locator                |
| HTML          | Hypertext Markup Language               |
| PDU           | Protocol Data Unit                      |
| PT            | Packet Tracer                           |

---

### Refreshers

#### 1. What is the purpose of twisting copper wires in a twisted pair cable?

The twisting helps reduce electromagnetic interference (EMI) and signal noise from external sources.

#### 2. Which connector is used to terminate Ethernet cables?

The RJ-45 (Registered Jack-45) connector is used for termination.

#### 3. What is the standard wiring sequence for T568B?

The sequence is: White/Orange, Orange, White/Green, Blue, White/Blue, Green, White/Brown, and Brown.

#### 4. When should a Straight-Through cable be used?

It is used to connect different types of network devices, such as a PC to a switch or hub.

#### 5. What is the function of a LAN cable tester?

It is used to verify the continuity of all eight wires and confirm the correct pin-to-pin mapping.

#### 6. What does the Domain Name System (DNS) do?

DNS translates human-readable domain names into numerical IP addresses for computer communication.

#### 7. Which protocol is specifically used for transferring files between a client and a server?

The File Transfer Protocol (FTP) is used for uploading and downloading files.

#### 8. What is the purpose of an "A Record" in a DNS server?

An A Record maps a domain name to the IPv4 address of a server (such as an HTTP server).

#### 9. Which FTP command is used to upload a file to a server?

The "put" command is used to upload files.

#### 10. Define a Virtual Local Area Network (VLAN).

A VLAN is a logical segmentation of a Layer 2 network that groups devices independently of their physical location.

#### 11. What is the "Normal VLAN Range"?

The normal range is from VLAN 2 to VLAN 1001.

#### 12. Which link type connects a PC to a VLAN-aware switch?

An Access Link is used for this connection.

#### 13. What standard is used for frame tagging in VLANs?

VLANs are implemented using IEEE 802.1Q frame tagging.

#### 14. What is a Trunk Link?

A Trunk Link connects VLAN-aware devices (like switch-to-switch) and carries traffic from multiple VLANs.

#### 15. How are traffic paths defined in Static Routing?

Paths are manually defined by a network administrator and remain fixed until updated.

#### 16. What is the metric used by the Routing Information Protocol (RIP)?

RIP uses hop count as its metric.

#### 17. What is the maximum hop limit allowed in RIP?

RIP has a limit of 15 hops.

#### 18. Which algorithm does RIP use to exchange routing tables?

RIP utilizes the Bellman-Ford algorithm.

#### 19. What does SSID stand for in wireless networking?

SSID stands for Service Set Identifier, which is the unique Network Name.

#### 20. Why is the DHCP server disabled on a secondary router when connecting two wireless routers?

It is disabled so the primary router can act as the polling router, ensuring all devices belong to the same subnet.

---

### Theoretical Questions

<p align="center"><strong>Network Cabling and Standards</strong></p>

#### 1.1. Elaborate on the structural and functional differences between **Straight-Through** and **Crossover** cables, specifically highlighting their wiring standards and typical use cases.

Twisted pair cables consist of insulated copper wires twisted together to reduce electromagnetic interference (EMI) and signal noise. In Ethernet networking, these are terminated using RJ-45 connectors following TIA/EIA standards, namely T568A and T568B.

- A Straight-Through cable uses the same wiring standard (**usually T568B**) on both ends and is designed to **connect different types of devices**, such as a PC to a switch or hub.

- Conversely, a Crossover cable is created by **using T568A on one end and T568B on the other**. This configuration crosses the Transmit (**TX**) pairs (Pins 1 & 2) with the Receive (**RX**) pairs (Pins 3 & 6), making it suitable for connecting **similar devices**, such as **PC-to-PC** or **switch-to-switch**.

---

#### 1.2. Explain the mechanical process of crimping an RJ45 connector and the specific role of a LAN cable tester in verifying the result.

- Crimping is the process of using a specialized tool to terminate a twisted pair cable. When the tool is firmly squeezed, it simultaneously pushes eight gold pins into the individual copper wires to establish electrical contact and secures the cable jacket into the connector for strain relief.

- After termination, a LAN cable tester is essential to verify the cable’s integrity. It checks for continuity across all eight wires and ensures the pin-to-pin mapping is correct (_e.g.,_ ensuring Pin 1 on one end reaches Pin 1 on the other for straight-through cables), identifying any faults or miswiring before the cable is used in a live network.

---

#### 1.3. What are the T568A and T568B color codes?

- **T568A** Color Code Sequence:

    ```
    1: White-Green
    2: Green
    3: White-Orange
    4: Blue
    5: White-Blue
    6: Orange
    7: White-Brown
    8: Brown
    ```

- **T568B** Color Code Sequence:

    ```
    1: White-Orange
    2: Orange
    3: White-Green
    4: Blue
    5: White-Blue
    6: Green
    7: White-Brown
    8: Brown
    ```

In both standards, the Blue (Pins 4, 5) and Brown (Pins 7, 8) pairs remain in the same positions as they are generally not used for standard **10/100BASE-T** data transmission.

---

<br>
<p align="center"><strong>Application Layer Protocols</strong></p>
<br>

#### 2.1. Explain the distinct roles of **DNS**, **HTTP**, and **FTP** and how they interact to provide network services to an end-user.

These three are distinct application-layer protocols that enable specific network functions.

- DNS (**Domain Name System**) serves as the foundational step by translating human-readable domain names into numerical IP addresses that computers use for communication.

- Once the IP is obtained, HTTP (**Hypertext Transfer Protocol**) is used by web browsers to request and view content from web servers.

- FTP (**File Transfer Protocol**) is specialized for transferring files (uploading and downloading) between a client and a server, which is distinct from the general browsing function of HTTP. Administrators often use FTP to upload the very files that HTTP later serves to users.

---

#### 2.2. In the context of the Domain Name System (DNS), define Resource Records and explain their necessity for accessing a web server.

Resource Records are entries within a DNS server’s database that map human-readable names to specific data, most commonly IP addresses. For example, an "A Record" maps a domain name (like _www.bubt.com_) to the numerical IPv4 address of an HTTP server.

This is a foundational step because while humans prefer using names, computers require the numerical IP address to route traffic and establish connections. Without these records, a browser would be unable to find the correct server to send its HTTP requests.

---

#### 2.3. Describe the functionality of the "put" and "get" commands within an FTP session and the importance of User Setup for server access.

In an FTP (File Transfer Protocol) session, the `put` command is used to upload a file from a local client to the remote server. Conversely, the `get` command is used to download a file from the server to the client's local storage.

To manage these actions securely, administrators perform **User Setup**, which involves creating specific usernames and passwords and assigning granular permissions (such as **Read, Write, Delete, and List**). This ensures that only authorized users can modify or access sensitive files stored on the server.

---

<br>
<p align="center"><strong>Virtual Local Area Networks (VLANs)</strong></p>
<br>

#### 3.1. Define VLAN and differentiate between Access Links and Trunk Links in terms of their functionality and frame handling.

A VLAN is a **logical segmentation** of a **Layer 2 network** that groups devices into separate networks regardless of their physical location. It is **implemented on switches** using **IEEE 802.1Q frame tagging**. The communication between devices involves two main types of links:

- **Access Link:** This connects a VLAN-unaware device (like a PC) to a switch. Frames on this link are untagged and belong to only a single VLAN.

- **Trunk Link:** This connects VLAN-aware devices, such as switch-to-switch or switch-to-router links. It is designed to carry traffic from multiple VLANs simultaneously by using tagging to identify which frame belongs to which network.

---

#### 3.2. Differentiate between the Normal VLAN Range and the physical constraints of a traditional LAN.

A traditional LAN is defined by physical topology, meaning devices must be physically connected to the same switch or segment to be on the same network. A VLAN, however, uses **IEEE 802.1Q frame tagging** to segment a network logically, regardless of physical location.

The Normal VLAN Range spans from **VLAN 2 to VLAN 1001**. VLANs in this range are stored in the switch's database and are fully configurable, meaning an administrator can create, edit, or delete them as needed to reorganize the network without moving a single cable.

---

#### 3.3. Elaborate on the advantages of using the CLI for VLAN configuration and list the essential commands used to assign a port to a specific VLAN.

While manual GUI configuration is possible, the CLI offers more precision and the ability to configure ranges of ports simultaneously, which is more efficient for large-scale setups. Essential commands include:

- `vlan [number] and name [name]` to define the VLAN in the database.
- `interface range [port-range]` to select multiple ports at once.
- `switchport mode access` to define the port's link type.
- `switchport access vlan [number]` to logically assign those ports to the specific network.

---

#### 3.4. How do you configure a trunk link in CLI?

To configure a trunk link using the **Command Line Interface** (CLI), you must identify the specific port or range of ports connecting two VLAN-aware devices (such as switch-to-switch or switch-to-router) and define their mode as "Trunk".

- **Access the CLI:** Open the switch's configuration window and navigate to the CLI tab.
- **Enter Configuration Mode:** Type the following commands to move from user mode to global configuration mode:

    ```
    enable
    config t (or configure terminal)
    ```

- **Select the Interface:** Identify which port connects to the other switch and enter its interface configuration mode. For example, if the switches are connected via port FastEthernet 0/7, you would type:

    ```
    interface range Fa0/7
    ```

- **Set Mode to Trunk:** Use the switchport command to designate the link as a trunk, which allows it to carry traffic from multiple VLANs using IEEE 802.1Q tagging:

    ```
    switchport mode trunk
    ```

This configuration is essential because, unlike access links which only belong to a single VLAN and carry untagged frames, trunk links are required to pass traffic for all configured VLANs across the network backbone.

---

#### 3.5. Explain the significance of IEEE 802.1Q tagging in VLANs.

IEEE 802.1Q tagging is the **standard protocol** used to implement **Virtual Local Area Networks** (VLANs) on switches. Its primary significance lies in enabling the logical segmentation of a **Layer 2 network**, which allows devices to be grouped into separate networks regardless of their physical location.

While Access Links connect VLAN-unaware devices and carry untagged frames belonging to only a single VLAN, Trunk Links rely on IEEE 802.1Q tagging to carry traffic from multiple VLANs simultaneously. This tagging mechanism identifies which logical network a frame belongs to as it travels across shared physical connections, such as switch-to-switch or switch-to-router links.

By using this standard, a network can achieve higher levels of network isolation and data privacy, ensuring that sensitive data from one department (like Finance) remains logically separated from another (like IT), even when they share the same physical hardware. Ultimately, IEEE 802.1Q tagging **allows for a more flexible and secure network infrastructure** that is defined by logical requirements rather than restricted by physical topology.

---

#### 3.6. What are the core differences between Access and Trunk links?

In a Virtual Local Area Network (VLAN) environment, the core differences between Access Links and Trunk Links center on the types of devices they connect, how they handle VLAN membership, and their use of frame tagging.

1.  **Connected Devices**
    - **Access Link:** This type of link connects a VLAN-unaware end device, such as a desktop PC, to a VLAN-aware switch.

    - **Trunk Link:** This link is used to interconnect VLAN-aware devices, such as connecting one switch to another switch or a switch to a router.

2.  **VLAN Membership and Traffic**
    - **Access Link:** Traffic on an access link belongs to only a single, specific VLAN. In a laboratory setting, a port is manually assigned to a single VLAN ID, such as VLAN 10 (IT) or VLAN 20 (HR).

    - **Trunk Link:** A trunk link is designed to carry traffic from multiple VLANs simultaneously across the same physical connection.

3.  **Frame Tagging (IEEE 802.1Q)**
    - **Access Link:** Frames transmitted over these links are untagged. Because the end device is unaware of the VLAN structure, the switch handles the logical separation internally.

    - **Trunk Link:** To distinguish between traffic from different networks, trunk links use IEEE 802.1Q frame tagging. This protocol adds a "tag" to each frame to identify which VLAN it belongs to as it travels between switches.

4.  **Command Line Interface (CLI) Configuration**

    **For Access Links:** An administrator must first define the mode and then assign the specific VLAN:

        switchport mode access
        switchport access vlan [number]

    **For Trunk Links:** The administrator only needs to define the port as a trunk to allow all VLAN traffic to pass:

        switchport mode trunk

---

<br>
<p align="center"><strong>Network Routing Methodologies</strong></p>
<br>

#### 4.1. Compare Static Routing and RIP (Routing Information Protocol), discussing their mechanisms, metrics, and ideal network environments.

- **Static Routing** involves paths manually defined by a network administrator that remain fixed until updated. It offers predictability, high security, and low overhead, making it ideal for small and simple networks.

- In contrast, **RIP** is a dynamic distance-vector protocol that uses the Bellman-Ford algorithm to exchange routing tables with neighbors every 30 seconds. RIP uses hop count as its metric, with a **maximum limit of 15 hops**, making it suitable for small networks but not scalable for larger ones.

While **static routing requires manual configuration** for every route, **RIP automates the process** by allowing routers to learn paths from their neighbors.

---

#### 4.2. Why is Static Routing considered more predictable and secure than dynamic methods, and what are its primary drawbacks?

Static routing is predictable because the paths are manually defined by an administrator and do not change unless the admin intervenes. This strict control prevents routers from automatically learning potentially malicious or inefficient routes from other devices, enhancing security.

It also has low overhead because routers do not need to constantly exchange routing tables.

However, its primary drawback is that it is not scalable; in a large network, manually updating every route for every change becomes complex and prone to human error.

---

#### 4.3. Explain the significance of Hop Count as a metric in RIP and why the protocol is limited to 15 hops.

In RIP (**Routing Information Protocol**), the metric used to determine the best path is the hop count, which represents the number of routers a packet must pass through to reach its destination. RIP is limited to 15 hops; any destination that is 16 or more hops away is considered unreachable. This limitation is a design choice that prevents routing loops from continuing indefinitely but also means RIP is only suitable for small, simple networks and cannot be used for large, global internetworks.

---

#### 4.4. Describe the mechanism of the Bellman-Ford algorithm as applied in RIP routing updates.

RIP uses the **Bellman-Ford algorithm** to maintain its routing table. Every 30 seconds, each router broadcasts its entire routing table to all its immediate neighbors. When a neighbor receives this information, it uses the algorithm to compare the received paths with its own.

If the neighbor's table shows a path with a lower hop count to a destination, the router updates its table to reflect the better route. This allows the network to eventually reach a state of convergence where all routers know the shortest paths available.

---

<br>
<p align="center"><strong>Wireless Routing and Security</strong></p>
<br>

#### 5.1. Discuss the purpose of Wireless Routing and the significance of SSID and WPA2-Personal in its configuration.

Wireless Routing directs data packets between nodes over a wireless medium, providing high mobility for devices like smartphones and laptops. It typically operates on radio frequencies such as **2.4 GHz** or **5 GHz**.

- A critical component is the SSID (**Service Set Identifier**), which serves as the unique network name that allows client devices to identify and connect to the correct wireless network.

- To protect data privacy, security protocols like **WPA2-Personal** (WPA2-PSK) are implemented, which require a passphrase to authenticate users and encrypt wireless traffic, ensuring that only authorized individuals can access the network.

---

#### 5.2. Discuss the distinct roles of the SSID and WPA2-Personal in managing a wireless network.

The SSID (**Service Set Identifier**) acts as the Network Name, allowing wireless client devices (like laptops or smartphones) to identify and distinguish one wireless network from another in a crowded area. However, the SSID does not provide security.

**WPA2-Personal** (also known as WPA2-PSK) is the security protocol used to protect the network. It requires a passphrase for authentication and uses AES encryption to protect the data transmitted over the airwaves, ensuring that even if someone sees the SSID, they cannot join the network or intercept data without the correct key.

---

#### 5.3. Explain the rationale for disabling the DHCP Server on a secondary router when interconnecting two wireless routers.

When two wireless routers are interconnected to expand a network, they should typically belong to the same subnet to allow seamless traffic sharing. If both routers have their DHCP (Dynamic Host Configuration Protocol) servers enabled, they might issue conflicting IP addresses to clients or place them on different logical subnets, causing communication failures.

By disabling DHCP on the secondary router, the primary router (often called the **polling router**) becomes the sole authority for assigning IP addresses. This ensures all devices across both routers are on a single, unified network.

---

#### 5.4. How do you configure the NIM-2T module on a router?

To configure the NIM-2T module on a router (such as the **ISR4331**):

- Open the router's configuration window and navigate to the Physical tab.
- You must turn off the router before adding hardware modules.
- Select the NIM-2T module from the left sidebar and drag it into an available slot on the router’s physical chassis. The **NIM-2T** is a 2-port multi-protocol synchronous serial **Network Interface Module**.
- Turn the router back on and allow it several minutes to complete its boot process.
- Once the module is installed and the router is running, navigate to the **Config** tab. You will now see new serial interfaces (such as **Serial0/1/0** and **Serial0/1/1**). You can then configure these with the appropriate IPv4 Addresses and Subnet Masks, ensuring you also turn the port status to "On".

---

#### 5.5 What is the function of the polling router?

A polling router acts as the primary authority for a unified network when multiple wireless routers are interconnected. Its specific functions and the rationale for its setup include:

- **Centralized DHCP Management:** When two wireless routers (such as **Router0** and **Router1**) are connected to share network traffic, they must belong to the same subnet. To achieve this, the DHCP server is disabled on the secondary router, making the remaining active router the "polling router" that handles all IP address assignments for the entire network.

- **Unified Network Traffic:** By acting as the sole DHCP authority, the polling router ensures that all client devices—regardless of which physical router they are wirelessly connected to—reside on the same logical network segment, allowing them to communicate and share data seamlessly.

- **Extended Functionality:** Connecting to a polling router allows for the extension of network services, such as providing all connected clients with access to a centralized FTP server.

---
