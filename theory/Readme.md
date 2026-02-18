## Mid Term Examination

### Topic List

1. [**Definitions**](#definitions)
    - Throughput
    - Network Protocol
    - Internet
    - Hosts & Links
    - Packet Loss
    - Packet Switching
    - Circuit Switching
    - Delay
    - Latency
    - Routing and Forwarding
    - FDM & TDM
    - Bottleneck Link
    - Virus & Worm, Botnet
    - DoS
    - Packet Interception
    - RTT (Round Trip Time)
    - Caesar Cipher
    - Acknowledgment Number
    - TTL (Time to Live)
    - Hop
    - Subnet Mask
    - Default Gateway
    - Subnetting

2. [**Theoretical Question**](#theoretical-questions)
    - **Chapter I**
        - [Explain Throughput and Bandwidth](#11-explain-throughput-and-bandwidth)
        - [Packet Switching vs Circuit Switching](#12-packet-switching-vs-circuit-switching)
        - [Four Types of E2E Delays](#13-four-types-of-e2e-delays)
        - [Packet Interception](#14-packet-interception)
        - DDoS Attack
        - Why Layering is Required in Networking?
        - Elaborate Internet Protocol Stack
        - Cerf and Khan’s Internetworking Principles
        - Reference Models: OSI, ISO, TCP/IP
        - End-to-End Communication
        - E2E Throughput
        - Why do packet loss and delay occur?

    - **Chapter II**
        - Client-Server Model
        - Peer-to-Peer Model
        - Sockets
        - Addressing Process
        - Web (HTTP) Protocol
        - HTTP Connection Types
        - HTTP Request Methods
        - HTTP Response Codes
        - Maintaining User/Server States (Cookies)
        - Components of Cookies
        - Cookie Mechanism
        - Web Caching (Proxy Servers) with Example
        - Conditional GET
        - Mitigating HOL Blocking (HTTP/2)
        - SMTP and its Components
        - IMAP
        - DNS: Services & Structure
        - DNS: Tree
        - TLD & Authoritative DNS
        - Queries: Iterated & Recursive
        - DNS Records: Components
        - FTP: Process, Commands & Status Codes
        - POP3 IMAP
        - IP Addressing: Classes A-E
        - Cryptographic Components

    - **Chapter III**
        - TCP vs UDP
        - UDP Segment Headers
        - TCP Segment Structure

    - **Chapter IV**
        - IPv4 Packet Structure
        - IPv6 Packet Structure
        - What happens when TTL is zero?
        - What is a fragment?
        - Explain each field in IP Datagram (v4, v6)
        - IPv6 Flow Label
        - TCP Congestion Control: AIMD
        - Why is AIMD used?
        - TCP Slow Starts

3. [**Mathematical Questions**](#mathematical-questions)
    - Packet Queueing Delay
    - Nodal Delay
    - IP Addressing
    - Identify Class by converting IP to Binary
    - Monoalphabetic and Polyalphabetic Cipher
    - Internet Checksum
    - TCP RTT
    - TCP Timeout

### Full Forms

| Abbreviation | Full Form                                 |
| :----------- | :---------------------------------------- |
| FDM          | Frequency Division Multiplexing           |
| TDM          | Time-Division Multiplexing                |
| DoS          | Denial of Service                         |
| ACK          | Acknowledgment Number                     |
| RTT          | Round Trip Time                           |
| TTL          | Time to Live                              |
| AP           | Access Point                              |
| LAN          | Local Area Network                        |
| AIMD         | Additive Increase/Multiplicative Decrease |

### Definitions

- <ins><strong>Throughput:</strong></ins> The actual rate of successful data delivery over a network channel within a specific period of time.

- <ins><strong>Network Protocol:</strong></ins> A standardized set of rules, conventions, and data structures that govern how devices on a network format, transmit, receive, and interpret data.

- <ins><strong>Internet:</strong></ins> A global, _decentralized network_ of interconnected computers and devices using standardized protocols (**TCP/IP**) to communicate, acting as a "network of networks" to facilitate information exchange.

- <ins><strong>Host:</strong></ins> Any device connected to a network that has a unique IP address, enabling it to send, receive, and share data.

- <ins><strong>Link:</strong></ins> The physical or logical communication pathway connecting two or more nodes to allow data transmission. **Links are the foundation for network communication.**

- <ins><strong>Packet Loss:</strong></ins> Occurs when data packets fail to reach their destination on a network.

- <ins><strong>Packet Switching:</strong></ins> A fundamental, efficient data transmission method where data is broken into smaller _packets_ that travel accross a network (like Internet) to a destination.

- <ins><strong>Circuit Switching:</strong></ins> A _connection-oriented network technique_ that establishes a dedicated, exclusive physical path between two endpoints for the entire duration of a session.

- <ins><strong>Delay:</strong></ins> The total time that a packet takes to travel from the source to destination across a network.

- <ins><strong>Latency:</strong></ins> The time between data entering a device and leaving it.

- <ins><strong>Routing:</strong></ins> The process of selecting the best, most efficient paths for data packets to travel across interconnected networks from source to destination.

- <ins><strong>Forwarding:</strong></ins> The action a router or switch takes to pass a data packet from an input to the correct output, moving it closer to the destination.

- <ins><strong>Frequency Division Multiplexing (FDM):</strong></ins> An analog technique that combines multiple signals onto a single communication channel by assigning each signal a unique, non-overlapping frequency band.

- <ins><strong>Time-Division Multiplexing (TDM):</strong></ins> A networking technique that transmits multiple, independent data streams over a single channel by separating the signal into distinct, fixed-duration time slots.

- <ins><strong>Bottleneck Link:</strong></ins> The slowest or most constrained link along a data path, restricting overall maximum throughput of a connection.

- <ins><strong>Virus:</strong></ins> A malware that replicates by inserting its code into programs and boot sectors, requiring a host program to activate and spread across networks.

- <ins><strong>Worm:</strong></ins> A standalone, self-replicating malware that spreads across networks without requiring a host file or user interaction.

- <ins><strong>Botnet:</strong></ins> A collection of internet-connected, malware-infected devices (clients and servers) remotely controlled by a single attacker, known as a **Bot Herder**.

- <ins><strong>Denial of Service (DoS):</strong></ins> A malicious attempt to disrupt normal traffic of a targeted server, service, or network by overwhelming it with a flood of illegitimate requests, rendering it inaccessible to legitimate users.

- <ins><strong>Packet Interception:</strong></ins> Also known as **sniffing**, the act of capturing, monitoring, and analyzing data packets traversing a network to inspect their contents, such as unencrypted logins, passwords, and user traffic.

- <ins><strong>Round Trip Time (RTT):</strong></ins> The total time for a network request to travel from source to destination and returning back to the source again.

- <ins><strong>Caesar Cipher:</strong></ins> A **foundational**, simple substitution encryption technique in network security where each letter in plaintext is replaced by another letter a fixed number of positions down or up the alphabet.

- <ins><strong>Acknowledgment Number (ACK):</strong></ins> A 32-bit filed in the TCP header that indicates the sequence number of the next expected byte of data from the sender.

- <ins><strong>Time to Live (TTL):</strong></ins> A mechanism that _limits_ the lifespan of data (packets or DNS records), preventing from circulating indefinitely in a network.

- <ins><strong>Hop:</strong></ins> Occurs when a packet is passed from one network segment to the next.

- <ins><strong>Subnet Mask:</strong></ins> A 32-bit number paired with an IP address to divide it into network and host components, determining which part identifies the network and which identifies the host.

- <ins><strong>Default Gateway:</strong></ins> A network node (or router) that serves as the AP for data traversing from a LAN to external networks (the Internet).

- <ins><strong>Subnetting:</strong></ins> The logical process of dividing a large physical IP network into smaller, manageable sub-networks (_subnets_) to improve network performance, security, and address efficiency.

### Theoretical Questions

Thanks to **Amrin Jahan** for helping me write some of the answers given here.

#### 1.1. Explain Throughput and Bandwidth

<ins><strong>Throughput:</strong></ins> The actual rate of successful data delivery over a network channel within a specific period of time, typically measured in Mbps or Gbps.

> _If a network **sends 100 Mb data in 1 second**, the throughput is 100 Mbps._

<ins><strong>Bandwidth:</strong></ins> The (theoretical) maximum amount of data that can be sent through a network channel within a specific period of time.

> _If a network **can send up to 100 Mbps data**, then the bandwidth is 100 Mbps._

<ins><strong>Advantages and Disadvantages of Throughput:</strong></ins>

| **Advantages**                                | **Disadvantages**                             |
| :-------------------------------------------- | :-------------------------------------------- |
| • Higher system performance,                  | • Many factors may reduce throughput,         |
| • Efficient data transfer,                    | • Inconsistent at times,                      |
| • Medium of comparison of different networks. | • Does NOT reveal the true delay information. |

<ins><strong>Advantages and Disadvantages of Bandwidth:</strong></ins>

| **Advantages**                          | **Disadvantages**              |
| :-------------------------------------- | :----------------------------- |
| • (Theoretically) Higher data capacity, | • Costly,                      |
| • Better network performance,           | • Possibility of wastage,      |
| • Less congestion.                      | • Does NOT translate to speed. |

<ins><strong>Difference between Throughput and Bandwidth:</strong></ins>

| **Throughput**                                          | **Bandwidth**                                      |
| :------------------------------------------------------ | :------------------------------------------------- |
| The actual data rate sent through the network           | The theoretical maximum data capacity of a network |
| Shows how much data is _really sent_                    | Shows how much data _can be sent_                  |
| Measured usually in **Mbps, Gbps**                      | Measured usually in **Mbps, MBps,** or **Gbps**    |
| Throughput _can change_ depending on network conditions | Bandwidth is _fixed_                               |
| High throughput indicates high performance              | High bandwidth does NOT translate to high speed    |
| Depends on network traffic, delays, and errors          | Depends on network design and hardware             |

---

#### 1.2. Packet Switching vs Circuit Switching

| **Feature**       | **Packet Switching**      | **Circuit Switching** |
| :---------------- | :------------------------ | :-------------------- |
| **Connection**    | NO dedicated path         | Dedicated path        |
| **Dataflow**      | Data divided into packets | Continuous            |
| **Bandwidth Use** | Efficient                 | Inefficient           |
| **Delay**         | Variable                  | Fixed/predictable     |
| **Reliability**   | Network dependent         | Very high             |
| **Example**       | Internet                  | Telephone call        |

---

#### 1.3. Four Types of E2E Delays

End-to-end (E2E) delay is the total time a packet takes to travel from source to destination across a network. There are four key components of the E2E delay:

- <ins><strong>Transmission Delay (D<sub>trans</sub>):</strong></ins> The time required to push all bits of a data packet onto a network link.

<pre>D<sub>trans</sub> = L / R
   Where, L = Packet size
          R = Transmission Rate or Bandwidth</pre>

- <ins><strong>Propagation Delay (D<sub>prop</sub>):</strong></ins> The time it takes for a signal (bit) to travel from sender to receiver across a physical medium.
    - Signal speed: <strong>2×10<sup>8</sup> ms<sup>-1</sup></strong> for fiber optic cables.
    - Unlike transmission delay, propagation delay is independent of the data rate or packet size.

<pre>D<sub>prop</sub> = Distance / Speed</pre>

- <ins><strong>Processing Delay (D<sub>proc</sub>):</strong></ins> The time required for network devices (<strong>routers, switches, firewalls</strong>) to examine a packet's header, determine its destination, check for errors and perform security checks.

- <ins><strong>Queuing Delay (D<sub>queue</sub>):</strong></ins> The time a data packet spends waiting in a network device's buffer (queue) before it is transmitted, occurring when incoming traffic exceeds the outgoing link's capacity. **It is a major, variable source of network latency and congestion.**

**Calculating E2E Delay:**

<pre>D<sub>e2e</sub>&nbsp;=&nbsp;D<sub>trans</sub>&nbsp;+&nbsp;D<sub>prop</sub>&nbsp;+&nbsp;D<sub>proc</sub>&nbsp;+&nbsp;D<sub>queue</sub></pre>

---

#### 1.4. Packet Interception

Also known as **packet sniffing**, packet interception the act of capturing, monitoring, and analyzing data packets traversing a network to inspect their contents, such as unencrypted logins, passwords, and user traffic.

<ins><strong>Use Cases:</strong></ins>

- **Network Troubleshooting:** Identifying performance bottlenecks, congestion, and packet loss.
- **Security Analysis:** Detecting intrusions, malware, and suspicious traffic patterns.
- **Forensics:** Creating network activity log for investigation purposes.

<ins><strong>Techniques of Interception:</strong></ins>

- **SPAN**/Mirroring
- **Network TAPs**
- Software Sniffers (**Wireshark**)

<ins><strong>Prevention and Defence:</strong></ins>

- **Encryption:** Using HTTPS, SSL/TLS, and VPNs to make captured data unreadable.
- **Network Segmentation:** Limits the scope of what someone can monitor.
- **Secured Infrastructure:** Using secure switches and disabling unused ports to prevent unauthorized monitoring.

---

### Mathematical Questions
