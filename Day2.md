<b> Day - 2</b> <br>
# Infrastructure Security

- **Network Security**
  - FW (Firewall)
  - IDS/IPS (Intrusion Detection/Prevention Systems)

- **Application Security**

- **Endpoint Security**
  - EDR (Endpoint Detection and Response)
  - AV (Antivirus)

- **Email Security**
  - Phishing Mail
  - Email Gateway

- **Web Protection**
  - WAF (Web Application Firewall)

----------------------------------------------------------------------------------------------------------------------------
- **Network Security**
Network security is a critical part of cybersecurity focused on protecting an organization’s network and its data from unauthorized access, misuse, or destruction. It includes practices, policies, and technologies to safeguard the network infrastructure, covering things like data protection, user authentication, access control, and threat monitoring.

## Key Components in Network Security

### 1. Firewall
- A firewall acts as a barrier between a trusted internal network and untrusted external networks (like the internet). It inspects incoming and outgoing traffic and applies a set of rules to decide whether to allow or block data packets. Firewalls are often the first line of defense, filtering traffic based on IP addresses, port numbers, protocols, and specific content.
- **Types of firewalls:**
  - **Packet-filtering firewalls** – Filter packets based on predefined rules (like IP addresses, port numbers).
  - **Stateful inspection firewalls** – Track active connections and make more dynamic filtering decisions.
  - **Next-generation firewalls (NGFW)** – Offer advanced capabilities like intrusion prevention, deep packet inspection, and malware detection. *Example*: A firewall can block unauthorized access attempts from IP addresses outside the organization's trusted network.

### 2. Intrusion Detection System (IDS)
- An IDS monitors network traffic for suspicious or unusual activity that could indicate an intrusion or attack. It does not block the traffic but generates alerts for administrators to review.
- **Types of IDS:**
  - **Network-based IDS (NIDS)** – Monitors all network traffic, usually placed at strategic points like gateways.
  - **Host-based IDS (HIDS)** – Monitors traffic and activity on individual hosts or devices.
- IDS systems can use **signature-based detection** (matching traffic against known attack patterns) or **anomaly-based detection** (flagging traffic that deviates from normal behavior). *Example*: An IPS might block repeated login attempts from an unusual location, preventing brute-force attacks.

- **Application Security**
  - Protects applications by identifying and addressing vulnerabilities in code and configurations. This includes secure coding practices and patch management.  
    *Example*: A company implements input validation to prevent SQL injection attacks on its login page.

- **Endpoint Security**
  - **EDR (Endpoint Detection and Response)**: Monitors endpoints (like laptops and servers) for abnormal activity, providing detailed alerts for quick response.  
    *Example*: EDR software detects and isolates a compromised laptop showing signs of malware activity.
  - **AV (Antivirus)**: Detects and removes known malware threats such as viruses, trojans, and ransomware.  
    *Example*: Antivirus software identifies and removes a trojan horse embedded in a downloaded email attachment.

- **Email Security**
  - **Phishing Mail**: Uses tools to detect and block phishing emails that attempt to trick users into revealing sensitive information.  
    *Example*: An email security filter flags an email impersonating the CEO and asking employees to wire money to a fraudulent account.
  - **Email Gateway**: Filters emails to prevent spam, malware, and other harmful content from entering or leaving the organization.  
    *Example*: An email gateway blocks incoming emails containing malicious links or attachments to prevent malware infection.

- **Web Protection**
  - **WAF (Web Application Firewall)**: Filters and blocks malicious HTTP/S traffic, protecting web applications from common attacks.  
    *Example*: A WAF prevents an SQL injection attack on the company's e-commerce website, keeping customer data safe.
