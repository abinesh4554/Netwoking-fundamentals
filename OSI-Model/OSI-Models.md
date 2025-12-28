# OSI Model (Open Systems Interconnection)

## What is the OSI Model?
The OSI Model is a **7-layer reference model** that explains how data is transmitted from one device to another over a network.

It was developed by **ISO (International Organization for Standardization)**.

---

## Why OSI Model is Needed?
- Standardizes network communication
- Helps in understanding data flow
- Simplifies troubleshooting
- Used in network design and analysis

---

## OSI Model Layers (Top → Bottom)

| Layer No | Layer Name | Key Function |
|--------|-----------|-------------|
| 7 | Application | User interface & services |
| 6 | Presentation | Encryption, compression |
| 5 | Session | Session management |
| 4 | Transport | End-to-end delivery |
| 3 | Network | Routing & IP addressing |
| 2 | Data Link | MAC addressing |
| 1 | Physical | Hardware & signals |

---

## Layer 7: Application Layer
### Function
- Provides network services to end users

### Examples
- HTTP, HTTPS
- FTP
- SMTP
- DNS

### Interview Tip
- Closest layer to the user

---

## Layer 6: Presentation Layer
### Function
- Data formatting
- Encryption & decryption
- Compression

### Examples
- SSL/TLS
- JPEG, MP3 encoding

---

## Layer 5: Session Layer
### Function
- Establishes, manages, and terminates sessions
- Controls dialog between systems

### Example
- Login session handling

---

## Layer 4: Transport Layer
### Function
- End-to-end communication
- Error handling & flow control

### Protocols
- TCP (Reliable)
- UDP (Fast)

### Key Concepts
- Port numbers
- Segmentation

---

## Layer 3: Network Layer
### Function
- Logical addressing
- Routing between networks

### Examples
- IP (IPv4, IPv6)
- Routers

---

## Layer 2: Data Link Layer
### Function
- Physical addressing
- Frame delivery
- Error detection

### Examples
- MAC address
- Switches
- ARP

---

## Layer 1: Physical Layer
### Function
- Transmission of raw bits
- Hardware, cables, voltage levels

### Examples
- Ethernet cables
- Fiber optics

---

## Data Flow Example (OSI Perspective)

When you open a website:
1. Application layer creates request
2. Presentation layer encrypts data
3. Session layer manages session
4. Transport layer segments data
5. Network layer routes packets
6. Data Link layer frames data
7. Physical layer transmits bits

---

## Mnemonic to Remember OSI Layers
**A**ll  
**P**eople  
**S**eem  
**T**o  
**N**eed  
**D**ata  
**P**rocessing  

---

## Real-World Usage
- Used for troubleshooting
- Helps identify where issues occur
- Basis for TCP/IP model

---

## Interview Questions
**Q: Which layer does a router work on?**  
A: Network Layer (Layer 3)

**Q: Which layer handles encryption?**  
A: Presentation Layer (Layer 6)

**Q: Which layer uses port numbers?**  
A: Transport Layer (Layer 4)

---

## Summary
The OSI Model provides a structured way to understand networking and is essential for networking, cloud, and DevOps roles.
