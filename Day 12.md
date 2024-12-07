# OWASP Top 10 Vulnerabilities

1. **Broken Access Control**  
   Improper enforcement of access permissions allowing unauthorized users to access or manipulate data.

2. **Cryptographic Failures**  
   Weak encryption or poor implementation of cryptographic practices leading to data breaches.

3. **Injection**  
   Flaws where untrusted input is executed as code, such as SQL, NoSQL, or OS command injection.

4. **Insecure Design**  
   Weak system architecture or design flaws that fail to address security threats.

5. **Security Misconfiguration**  
   Incorrectly configured security settings or default settings not changed, exposing vulnerabilities.

6. **Vulnerable and Outdated Components**  
   Using outdated or unsupported software, libraries, or frameworks with known vulnerabilities.

7. **Identification and Authentication Failures**  
   Weak authentication mechanisms, such as default passwords or improper session handling.

8. **Software and Data Integrity Failures**  
   Trusting unverified software updates, dependencies, or compromised CI/CD pipelines.

9. **Security Logging and Monitoring Failures**  
   Lack of adequate logging, monitoring, or alerting, hindering detection of breaches or suspicious activity.

10. **Server-Side Request Forgery (SSRF)**  
    Exploiting server functionality to access unintended or sensitive resources.

---

# OSI Layers and Vulnerabilities

1. **Physical Layer**  
   - **Vulnerability**: Physical device tampering or unauthorized access.  
   - **Example**: A malicious actor physically disconnecting or modifying network cables.

2. **Data Link Layer**  
   - **Vulnerability**: ARP spoofing (Address Resolution Protocol manipulation).  
   - **Example**: Redirecting network traffic to an attacker's device.

3. **Network Layer**  
   - **Vulnerability**: IP spoofing.  
   - **Example**: Falsifying IP addresses to impersonate legitimate devices or bypass filters.

4. **Transport Layer**  
   - **Vulnerability**: TCP SYN flood attack.  
   - **Example**: Overloading the server with partial connections, causing a denial of service (DoS).

5. **Session Layer**  
   - **Vulnerability**: Session hijacking.  
   - **Example**: Stealing session tokens to impersonate a legitimate user.

6. **Presentation Layer**  
   - **Vulnerability**: Data exposure through insufficient encryption.  
   - **Example**: Sensitive data being transmitted in plaintext.

7. **Application Layer**  
   - **Vulnerability**: Cross-Site Scripting (XSS).  
   - **Example**: Injecting malicious scripts into web applications viewed by other users.
