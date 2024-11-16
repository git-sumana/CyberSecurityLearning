| **Feature**            | **IPv4**                                         | **IPv6**                                        |
|-------------------------|-------------------------------------------------|------------------------------------------------|
| **Address Length**     | 32-bit (4 bytes)                                | 128-bit (16 bytes)                             |
| **Address Format**     | Dotted decimal (e.g., 192.168.1.1)              | Hexadecimal colon-separated (e.g., 2001:0db8::1) |
| **Number of Addresses**| Approximately 4.3 billion                      | Virtually unlimited (340 undecillion)          |
| **Header Size**        | 20 bytes                                        | 40 bytes                                       |
| **Fragmentation**      | Done by both sender and routers                 | Done only by the sender                        |
| **Checksum**           | Includes a checksum                            | No checksum (handled by underlying layers)     |
| **Security**           | Optional (IPSec optional)                      | Mandatory (IPSec built-in)                     |
| **Configuration**      | Manual or DHCP                                 | Automatic (Stateless Address Autoconfiguration) or DHCPv6 |
| **Broadcasting**       | Supports broadcasting                          | Does not support broadcasting (uses multicast) |
| **Routing Efficiency** | Less efficient due to smaller address space    | More efficient with hierarchical addressing    |
| **Support for Mobility**| Limited                                       | Better support for mobile devices             |
| **Compatibility**      | Requires NAT for address expansion             | Direct end-to-end connectivity                 |
| **Example Address**    | 192.168.1.1                                    | 2001:0db8:85a3:0000:0000:8a2e:0370:7334       |

| **Feature**            | **Switch**                                       | **Router**                                      |
|-------------------------|-------------------------------------------------|------------------------------------------------|
| **Primary Function**   | Connects devices within a single network (LAN)  | Connects multiple networks (e.g., LAN to WAN) |
| **OSI Layer**          | Operates at Data Link Layer (Layer 2) or Network Layer (Layer 3 for Layer 3 switches) | Operates at Network Layer (Layer 3)           |
| **Data Transmission**  | Uses MAC addresses to forward data              | Uses IP addresses to forward data             |
| **Packet Forwarding**  | Based on hardware (MAC address table)           | Based on software (routing table)             |
| **Broadcast Domain**   | Typically, one per VLAN                         | Each port is a separate broadcast domain       |
| **Device Connectivity**| Provides multiple ports for device connections  | Connects networks, typically with fewer ports |
| **Speed**              | Higher speed, designed for local traffic        | Lower speed
