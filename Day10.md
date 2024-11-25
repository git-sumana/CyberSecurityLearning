### Networking Concepts and Security Threats

1. **DHCP Spoofing and Starvation**:  
Dynamic Host Configuration Protocol (DHCP) is critical in assigning IP addresses to devices on a network. DHCP starvation attacks exhaust the pool of available IP addresses by simulating multiple fake DHCP requests, disrupting legitimate users. In contrast, DHCP spoofing tricks devices into connecting to a rogue server, potentially exposing sensitive data. These attacks often occur in unsecured local networks, highlighting the importance of using techniques like port security and DHCP snooping.

2. **DNS (Root, TLD, and Authoritative Servers)**:  
The Domain Name System (DNS) translates human-readable domain names (e.g., `example.com`) into IP addresses. DNS is hierarchical, starting with root servers (top-level entry points for all DNS queries), followed by Top-Level Domain (TLD) servers (e.g., `.com`, `.org`), and then authoritative servers that hold specific domain records. This layered architecture ensures efficient and distributed resolution of domain names, making DNS vital for the functioning of the internet.

3. **ARP and ARP Poisoning**:  
The Address Resolution Protocol (ARP) is used to map IP addresses to MAC addresses within a local network. ARP poisoning is a security threat where attackers send falsified ARP messages to associate their MAC address with a legitimate IP address. This allows them to intercept, modify, or disrupt traffic. Networks are most vulnerable to ARP poisoning in unprotected environments, but countermeasures like dynamic ARP inspection can mitigate risks.

4. **Remote Desktop Protocol (RDP)**:  
RDP is a protocol enabling remote access to another computer's graphical interface. Widely used in IT management, RDP simplifies tasks like troubleshooting and server management. However, it is also a target for brute force and malware attacks. Proper configuration, multi-factor authentication, and endpoint security are crucial to safeguarding RDP sessions from unauthorized access.  
