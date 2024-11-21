# TCP and UDP Overview

## TCP (Transmission Control Protocol)
**TCP (Transmission Control Protocol)** is a robust protocol designed for reliable communication between devices. Being connection-oriented, it ensures that data is delivered in sequence and without errors, making it ideal for scenarios where data integrity is critical. TCP uses mechanisms like acknowledgments, retransmissions, and flow control to maintain communication reliability. This protocol is widely used in applications such as web browsing, email services, and file transfers, where the loss or corruption of data is unacceptable.

## UDP (User Datagram Protocol)
**UDP (User Datagram Protocol)** is a lightweight, connectionless protocol optimized for speed and efficiency. Unlike TCP, it does not guarantee data delivery, making it a faster but less reliable option. Since it lacks features like error correction and acknowledgments, it is used in scenarios where speed is prioritized over reliability, such as live video streaming, online gaming, and voice-over-IP (VoIP). UDP's simplicity and low overhead make it a preferred choice for time-sensitive applications.

---

# ICMP (Internet Control Message Protocol)
**ICMP (Internet Control Message Protocol)** plays a crucial role in managing and troubleshooting network communication. Unlike TCP and UDP, ICMP is not used for transmitting data between devices but instead focuses on sending error messages and operational queries. Tools like `ping` and `traceroute` rely on ICMP to test connectivity and measure network latency. By enabling devices to report issues such as unreachable destinations or expired packets, ICMP helps maintain the efficiency and reliability of network operations.

---

# Registered and Unregistered Ports

## Port Classification:
**Ports** serve as communication endpoints in network connections, with specific ranges designated for different purposes. The **well-known ports (0–1023)** are reserved for widely used services like HTTP and DNS, ensuring consistency across devices and networks. The **registered ports (1024–49151)** cater to less standardized applications, typically assigned by IANA. In contrast, the **dynamic or unregistered ports (49152–65535)** are used temporarily, often chosen by the operating system for short-lived connections. This structured port system ensures orderly and efficient communication across diverse applications.

---

# Common TCP and UDP Ports

| **Service**       | **Protocol** | **Port** |
|--------------------|--------------|----------|
| HTTP              | TCP          | 80       |
| HTTPS             | TCP          | 443      |
| FTP (Data)        | TCP          | 20       |
| FTP (Control)     | TCP          | 21       |
| DNS               | UDP/TCP      | 53       |
| SMTP              | TCP          | 25       |
| Telnet            | TCP          | 23       |
| SSH               | TCP          | 22       |
| SNMP              | UDP          | 161/162  |
| DHCP              | UDP          | 67/68    |

Each port corresponds to a specific service or protocol, ensuring seamless communication between devices. For example, web servers typically listen on ports 80 (HTTP) and 443 (HTTPS) to handle requests, while DNS queries are handled over port 53. This mapping of ports to services enables organized data exchange across the internet.
