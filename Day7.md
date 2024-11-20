### Dynamic NAT
Dynamic NAT allows private IP addresses to be mapped to public IP addresses dynamically from a predefined pool. Each internal device gets a temporary public IP only when needed, and the mapping is removed once the session ends. This conserves public IP addresses but requires enough public IPs in the pool to meet demand.

### Exhaust Pooling
Exhaust pooling occurs when the pool of public IPs in a NAT configuration is fully utilized, and no additional IPs are available for new connections. This leads to connection delays or failures, as the system cannot assign a public IP for outgoing traffic until one becomes free.

### PAT (Port Address Translation)
Port Address Translation (PAT), also called NAT Overload, enables multiple private IP addresses to share a single public IP address by differentiating connections through unique port numbers. This is highly efficient and commonly used to conserve public IPs while supporting multiple devices on a network.

### TCP - Means of Communication
TCP (Transmission Control Protocol) is a reliable protocol for data communication, using specific handshakes:  
1. **Three-Way Handshake**: Establishes a connection between devices: SYN (initiate), SYN-ACK (acknowledge), and ACK (confirm).  
2. **Four-Way Handshake**: Gracefully terminates the connection: FIN (finish), ACK (acknowledge), FIN (close), and ACK (confirm closure).  

TCP ensures proper connection setup, data integrity, and controlled termination for secure and orderly communication.
