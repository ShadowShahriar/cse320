## Final Term Examination

### Topic List

> Thanks to **Amrin Jahan** for highlighting the important topics mentioned in **section 2**.

1. [**Definitions**](#definitions)
    - IP Address
    - Network Interface
    - Subnet
    - Subnetting
    - Supernetting
    - Host
    - NAT
    - CIDR
    - DHCP
    - Public Key
    - Private Key
    - IP Address Class
    - Private Address Space
    - VLSM
    - FLSM
    - Asymmetric Cryptography
    - Symmetric Cryptography
    - RSA
        - RSA Encryption
        - RSA Decryption
    - Flooding
    - Forwarding
    - Routing
    - Distance Vector Routing
    - Broadcast Storm
    - Reverse Path Forwarding
    - Spanning Tree Broadcast
    - Border Gateway Protocol
        - eBGP
        - iBGP
        - BGP Session
        - BGP Protocol Messages
    - Autonomous System
    - Scanning
        - Active Scanning
        - Passive Scanning
    - Base Station
    - Wireless Link
    - Handoff Infrastructure
    - Signal to Noise Ratio
    - Bit Error Rate
    - CDMA
    - CSMA/CA
    - CSMA/CD
    - Basic Service Set
    - Beacon Frames
    - Access Point
    - RTS and CTS
    - WiMax
    - Address Resolution Protocol
    - Ad Hoc Network

2. [**Theoretical Question**](#theoretical-questions)
    - **Chapter 4: IP Addressing and Subnetting**
        - [IP Address Structure](#B)
        - [Why Subnetting is Necessary?]()
        - [What is the slash notation in a subnet address?]()
        - [Classless Subnetting using CIDR]()
        - [How does a host get IP address within its network?]()
        - [How does a network get IP address for itself?]()
        - [Why DHCP is better than manual routing?]()
        - [What is NAT? Why it is useful?]()
        - [IP Address Classes]()
        - [Private Address Space]()
        - [Classful vs Classless Subnetting]()
        - [VLSM vs FLSM]()
        - [Example of VLSM and FLSM]()
        - [Apply FLSM to a network address and make it efficient by applying VLSM]()

    - **Chapter 5: Routing Protocols**
        - [Routing Protocol Classification](#B)
        - [Dijkstra's Link State Routing Algorithm]()
        - [Distance Vector Algorithm]()

    - **Chapter 7: Wireless and Mobile Networks**
        - [Flooding: Pros and Cons](#B)
        - [Flooding: Broadcast Storm]()
        - [Flooding: Spanning Tree Broadcast]()
        - [Forwarding vs Routing]()
        - [Reverse Path Forwarding]()
        - [Distance Vector Algorithm]()
        - [Border Gateway Protocol with Example]()
        - [BGP Messages]()
        - [BGP Routes]()
        - [Elements of a Wireless Network]()
        - [Ad Hoc Mode]()
        - [Wireless Link Characteristics]()
        - [SNR vs BER]()
        - [IEEE 802.11 Wireless LAN Mechanism]()
        - [CSMA/CA and CSMA/CD]()
        - [IEEE 802.11 MAC Protocol: CSMA/CA]()
        - [IEEE 802.11 Frame Addressing]()
        - [WiMax]()

    - **Chapter 8: Network Security**
        - [Explain Asymmetric Cryptography](#B)
        - [Explain Symmetric Cryptography]()
        - [What is RSA?]()
        - [How does RSA encryption work?]()
        - [How does RSA content is decrypted?]()

3. **Mathematical Questions**
    - [IP Addressing](#11-ip-addressing)
    - [Variable Length Subnet Mask](#12-variable-length-subnet-mask)
    - [RSA Algorithm](#13-rsa-algorithm)

### Full Forms

| Abbreviation | Full Form                                              |
| :----------- | :----------------------------------------------------- |
| **IP**       | Internet Protocol                                      |
| **NAT**      | Network Address Translation                            |
| **DHCP**     | Dynamic Host Configuration Protocol                    |
| **CIDR**     | Classless Inter-Domain Routing                         |
| **VSLM**     | Variable Length Subnet Mask                            |
| **FSLM**     | Fixed Length Subnet Mask                               |
| **RSA**      | Rivest-Shamir-Adleman                                  |
| **RPF**      | Reverse Path Forwarding                                |
| **ACK**      | Acknowledgement                                        |
| **DVR**      | Distance Vector Routing                                |
| **STP**      | Spanning Tree Protocol                                 |
| **BGP**      | Border Gateway Protocol                                |
| **eBGP**     | External BGP                                           |
| **iBGP**     | Internal/Logical BGP                                   |
| **AS**       | Autonomous System                                      |
| **SNR**      | Signal to Noise Ratio                                  |
| **BER**      | Bit Error Rate                                         |
| **CDMA**     | Code Division Multiple Access                          |
| **CSMA/CA**  | Carrier Sense Multiple Access with Collision Avoidance |
| **CSMA/CD**  | Carrier Sense Multiple Access with Collision Detection |
| **BSS**      | Basic Service Set                                      |
| **AP**       | Access Point                                           |
| **RTS**      | Request to Send                                        |
| **CTS**      | Clear to Send                                          |
| **WiMax**    | Worldwide Interoperability for Microwave Access        |
| **ARP**      | Address Resolution Protocol                            |
| **MANET**    | Mobile Ad Hoc Network                                  |
| **WANET**    | Wireless Ad Hoc Network                                |
| **FANET**    | Flying Ad Hoc Network                                  |
| **VANET**    | Vehicular Ad hoc Network                               |

### Definitions

- <ins><strong>IP Address:</strong></ins> An IP (Internet Protocol) address is a unique numerical label that acts as a digital address for identifying devices (hosts) and locating them.

- <ins><strong>Network Interface:</strong></ins> A Network Interface is the hardware or software component that enables a device to connect to a computer network and exchange data.

- <ins><strong>Subnet:</strong></ins> A subnet (subnetwork) is a logical subdivision of an IP network, dividing a large network into smaller, manageable, and more efficient segments.

- <ins><strong>Subnetting:</strong></ins> Subnetting is the process of dividing a large IP network into smaller logical networks called subnets.

- <ins><strong>Supernetting:</strong></ins> Supernetting is a network technique that combines multiple smaller, contiguous IP networks (subnets) into a single, larger network, or supernet.

- <ins><strong>Host:</strong></ins> A network host is a computer or other device connected to a computer network.

- <ins><strong>NAT:</strong></ins> Network Address Translation (NAT) is a method used by routers to map multiple private IP addresses from a local network to a single public IP address for internet access.

- <ins><strong>CIDR:</strong></ins> Classless Inter-Domain Routing (CIDR) is a method for allocating IP addresses and routing IP packets more efficiently than the old class-based system.

- <ins><strong>DHCP:</strong></ins> Dynamic Host Configuration Protocol (DHCP) is a network management protocol that automatically assigns unique IP addresses to devices connected to a network.

- <ins><strong>Public Key & Private Key:</strong></ins> Public and private keys are a pair of long, alphanumeric strings used in asymmetric cryptography to secure digital information.

    The public key is shared openly to encrypt data or verify signatures, while the private key is kept secret by the owner to decrypt data or create digital signatures.

- <ins><strong>IP Address Class:</strong></ins> IP address classes (Classful Networking) are a method for dividing IPv4 addresses into five distinct categories (A, B, C, D, and E) to structure network sizes.

- <ins><strong>Private Address Space:</strong></ins> Private Address Space consists of reserved IP address ranges (defined by **RFC 1918**) used for internal networks (LANs), such as homes and offices, which are not routable on the public internet.

- <ins><strong>VSLM:</strong></ins> Variable Length Subnet Mask (VLSM) is an IP addressing technique that allows network engineers to divide an IP address space into subnets of different sizes.

- <ins><strong>FLSM:</strong></ins> FLSM (Fixed Length Subnet Mask) is a subnetting technique where all subnets in a network are designed to have an identical size and subnet mask.

- <ins><strong>Asymmetric Cryptography:</strong></ins> Asymmetric cryptography, is a security system that uses a pair of mathematically related keys: a public key for encryption (_freely shared_) and a private key for decryption (_kept secret_).

- <ins><strong>Symmetric Cryptography:</strong></ins> Symmetric cryptography is a type of encryption where a single, shared secret key is used for both encrypting and decrypting data.

- <ins><strong>RSA Encryption:</strong></ins> RSA (Rivest-Shamir-Adleman) encryption is a foundational asymmetric public-key cryptographic system widely used to secure sensitive data transmission.

- <ins><strong>RSA Decryption:</strong></ins> RSA decryption is the process of reverting ciphertext back into its original plaintext using a private key in the asymmetric RSA algorithm.

- <ins><strong>Flooding:</strong></ins> Flooding is a non-adaptive, static routing technique where a source node or router sends incoming packets out through every connected outgoing link, except the one used to receive the packet.

- <ins><strong>Forwarding:</strong></ins> Forwarding is the process where a router or switch receives a data packet on an input interface and moves it to the appropriate output interface, based on a forwarding table.

- <ins><strong>Routing:</strong></ins> Routing is the process of selecting the best path for data packets to travel across one or more interconnected networks from source to destination.

- <ins><strong>Distance Vector Routing:</strong></ins> Distance Vector Routing (DVR) is a protocol where each router keeps a table showing the distance (in hops) to all other routers.

- <ins><strong>Broadcast Storm:</strong></ins> A broadcast storm is a severe network performance issue where excessive broadcast or multicast traffic floods a network, causing it to slow down or completely collapse.

- <ins><strong>Reverse Path Forwarding:</strong></ins> Reverse Path Forwarding (RPF) is a network technique primarily used in multicast routing to prevent loops by verifying that a packet arrived on the interface closest to its source.

- <ins><strong>Spanning Tree Broadcast:</strong></ins> The Spanning Tree Protocol (STP) is a network protocol that builds a loop-free logical topology for Ethernet networks.

- <ins><strong>Border Gateway Protocol:</strong></ins> The Border Gateway Protocol (BGP) is the standardized exterior gateway protocol designed to exchange routing and reachability information among autonomous systems (AS) on the internet.
    - <ins><strong>eBGP:</strong></ins> eBGP is for talking between different networks.

    - <ins><strong>iBGP:</strong></ins> iBGP is for talking inside one network.

    - <ins><strong>BGP Session:</strong></ins> A BGP session is a reliable TCP-based connection (using **port 179**) between two routers, known as BGP peers or speakers, that exchange routing information to determine the best path for data across the internet.

    - <ins><strong>BGP Protocol Messages:</strong></ins> BGP Protocol Messages are the four fundamental packet types: Open, Update, Keepalive, and Notification.

- <ins><strong>Autonomous System:</strong></ins> An Autonomous System (AS) in BGP is a large, independently managed network or group of networks that shares a unified routing policy.

- <ins><strong>Active Scanning:</strong></ins> Active scanning involves sending direct probes or traffic to devices to detect vulnerabilities and gather detailed information.

    It is often used in penetration testing.

- <ins><strong>Passive Scanning:</strong></ins> Passive scanning involves monitoring existing network traffic without disrupting it to identify assets and vulnerabilities, providing a quieter, continuous, and non-intrusive security analysis.

- <ins><strong>Base Station:</strong></ins> A base station is a fixed radio transceiver that serves as the central hub for wireless communication networks, connecting mobile devices (phones, tablets) to the core network.

- <ins><strong>Wireless Link:</strong></ins> A wireless link is a communication connection that transfers data between devices using electromagnetic waves (radio or infrared) rather than physical cables.

- <ins><strong>Handoff Infrastructure:</strong></ins> Handoff infrastructure (or handover infrastructure) refers to the network components, protocols, and mechanisms that allow a mobile user to maintain a seamless connection, such as a voice call or data session, while moving between different base stations, access points, or network types.

- <ins><strong>Signal to Noise Ratio:</strong></ins> Signal-to-noise ratio (SNR) is a measure used to compare the level of a desired signal (like audio, data, or an image) to the level of background noise.

- <ins><strong>Bit Error Rate:</strong></ins> Bit Error Rate (BER) is the ratio of bits received in error to the total number of bits transmitted.

- <ins><strong>CDMA:</strong></ins> Code Division Multiple Access (CDMA) is a digital cellular technology that allows multiple users to share the same frequency band simultaneously without interference.

- <ins><strong>CSMA/CA:</strong></ins> Carrier Sense Multiple Access with Collision Avoidance (CSMA/CA) is a network contention protocol used primarily in wireless (Wi-Fi) networks to prevent data collisions.

- <ins><strong>CSMA/CD:</strong></ins> CSMA/CD (Carrier Sense Multiple Access with Collision Detection) is a network protocol used in wired Ethernet (IEEE 802.3) to manage shared transmission media. It allows devices to "listen" before transmitting, stop if a collision occurs, and wait a random time before retrying.

- <ins><strong>Basic Service Set:</strong></ins> A Basic Service Set (BSS) is the fundamental building block of an IEEE 802.11 (Wi-Fi) wireless local area network (WLAN).

- <ins><strong>Beacon Frames:</strong></ins> A beacon frame is a type of management frame in IEEE 802.11 WLANs.

- <ins><strong>Access Point:</strong></ins> An access point (AP) is a networking device that creates a wireless local area network (WLAN), typically in an office or large building.

- <ins><strong>RTS and CTS:</strong></ins> RTS (Request to Send) and CTS (Clear to Send) are hardware flow control signals used in serial communications (RS-232) and wireless networking (802.11) to manage data transmission, preventing data loss or collisions.

    RTS tells the receiver that a device wants to send data, and CTS tells the sender it is safe to transmit.

- <ins><strong>WiMax:</strong></ins> WiMAX (Worldwide Interoperability for Microwave Access) is a 4G-era wireless communication technology based on the IEEE 802.16 standard. It acts as a long-range, high-speed alternative to wired broadband.

- <ins><strong>Address Resolution Protocol:</strong></ins> ARP (Address Resolution Protocol) maps an IPv4 address to the corresponding MAC address on a local network so frames can be delivered to the correct device.

- <ins><strong>Ad Hoc Network:</strong></ins> An ad hoc network is a decentralized, temporary wireless network that connects devices directly without relying on central infrastructure like routers or access points.

### Theoretical Questions

#### 1.1. TODO

### Mathematical Questions

#### 1.1. IP Addressing

#### 1.2. Variable Length Subnet Mask

#### 1.3. RSA Algorithm
