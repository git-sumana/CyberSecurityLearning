# Protocols in the OSI Model

### 1. **Physical Layer**

- **Ethernet:** A widely used LAN technology that defines wiring, signaling, and framing standards for communication in local area networks.
- **Wi-Fi:** A wireless networking technology based on the IEEE 802.11 standards that enables devices to connect to the internet without physical cables.
- **Bluetooth:** A short-range wireless communication standard used for exchanging data between devices like smartphones, laptops, and peripherals.
- **USB (Universal Serial Bus):** A standard for connecting peripheral devices (e.g., keyboards, mice, storage) to computers and transferring data.
- **DSL (Digital Subscriber Line):** A family of technologies used for high-speed internet access over traditional copper telephone lines.

### 2. **Data Link Layer**

- **Ethernet:** Provides data link layer addressing and error-checking in wired local area networks through MAC addresses.
- **PPP (Point-to-Point Protocol):** A data link layer protocol used to establish a direct connection between two network nodes, commonly used in dial-up Internet connections.
- **Frame Relay:** A wide-area network protocol used for data transmission, offering high-performance, low-cost frame-switching for connecting LANs over large distances.
- **ARP (Address Resolution Protocol):** A protocol used to map a device's IP address to its corresponding MAC address on a local network.
- **Wi-Fi (IEEE 802.11):** A set of standards for wireless local area networks (WLAN), operating at the data link layer to provide wireless access to networks.

### 3. **Network Layer**

- **IP (Internet Protocol):** A core protocol that provides logical addressing and routing, ensuring data is sent across networks from source to destination, using either IPv4 or IPv6.
- **ICMP (Internet Control Message Protocol):** Used for diagnostic and error-reporting purposes, ICMP helps manage network communication, including tools like `ping` for network connectivity checks.
- **OSPF (Open Shortest Path First):** A link-state routing protocol used within large enterprise networks to find the best path for routing IP packets.
- **BGP (Border Gateway Protocol):** A path vector protocol used to exchange routing information between autonomous systems on the internet, making it crucial for inter-domain routing.
- **RIP (Routing Information Protocol):** A distance-vector routing protocol used in small to medium-sized networks, relying on hop count as the metric for determining the best path.

### 4. **Transport Layer**

- **TCP (Transmission Control Protocol):** A reliable, connection-oriented protocol that ensures the ordered and error-free delivery of data between applications over a network.
- **UDP (User Datagram Protocol):** A connectionless protocol that allows fast, low-latency transmission of data without ensuring reliability or error correction.
- **SCTP (Stream Control Transmission Protocol):** A message-oriented transport layer protocol that combines the benefits of TCP and UDP and provides features like multi-homing and message sequencing.

### 5. **Session Layer**

- **NetBIOS (Network Basic Input/Output System):** A protocol that allows applications on different computers to communicate within a local area network (LAN), often used in older Windows networking.
- **RPC (Remote Procedure Call):** A protocol that allows a program to execute a procedure (subroutine) on a different machine as if it were local, enabling distributed computing.
- **SMB (Server Message Block):** A protocol that provides file and printer sharing services, typically used in Windows networks for accessing files over the network.
- **PPTP (Point-to-Point Tunneling Protocol):** A VPN protocol that enables secure communication between remote users and a network by encapsulating data in a tunnel.

### 6. **Presentation Layer**

- **SSL/TLS (Secure Sockets Layer / Transport Layer Security):** Cryptographic protocols that ensure secure communication over a computer network by encrypting data and providing authentication.
- **JPEG (Joint Photographic Experts Group):** A standard method for compressing and encoding digital images, widely used in web and photography applications.
- **GIF (Graphics Interchange Format):** An image format that supports lossless compression and is commonly used for simple graphics and animations on the web.
- **TIFF (Tagged Image File Format):** A versatile image format used in professional photography and publishing for high-quality raster graphics.
- **MPEG (Moving Picture Experts Group):** A family of digital video and audio compression standards used in the creation of multimedia content such as movies and video streaming.
- **ASCII (American Standard Code for Information Interchange):** A character encoding standard used for representing text in computers, using 7 or 8 bits for each character.
- **EBCDIC (Extended Binary Coded Decimal Interchange Code):** A character encoding system used by IBM mainframe and midrange computer systems.

### 7. **Application Layer**

- **HTTP/HTTPS (Hypertext Transfer Protocol / Secure):** The foundation of data communication on the web, HTTP is used for transferring web pages, while HTTPS adds encryption for secure browsing.
- **FTP (File Transfer Protocol):** A protocol used to transfer files between computers over a network, allowing users to upload and download files from servers.
- **SMTP (Simple Mail Transfer Protocol):** A protocol used for sending and routing email between mail servers, part of the email delivery process.
- **POP3 (Post Office Protocol 3):** A protocol used by email clients to retrieve emails from a mail server, typically used for downloading and reading messages offline.
- **IMAP (Internet Message Access Protocol):** A protocol that allows email clients to access and manage messages on a mail server, with features like synchronized mail folders across devices.
- **DNS (Domain Name System):** A system that translates human-readable domain names (like `example.com`) into IP addresses that computers use to identify each other on a network.
- **DHCP (Dynamic Host Configuration Protocol):** A network management protocol that assigns dynamic IP addresses to devices on a network, simplifying IP address management.
- **SNMP (Simple Network Management Protocol):** A protocol used for monitoring and managing network devices like routers, switches, and servers, providing information about device health and performance.

