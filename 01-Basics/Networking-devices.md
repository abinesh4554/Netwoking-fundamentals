# Networking Devices

## What are Networking Devices?
Networking devices are hardware components that **connect, manage, and control** data flow between devices in a network.

---

## 1. Hub
### Description
A basic device that sends data to **all connected devices**.

### Characteristics
- Works at Physical Layer (Layer 1)
- No intelligence

### Drawbacks
- High collisions
- Rarely used today

---

## 2. Switch
### Description
A smart device that sends data **only to the intended device** using MAC addresses.

### Characteristics
- Works at Data Link Layer (Layer 2)
- Faster and efficient

### Usage
- LAN networks

---

## 3. Router
### Description
Connects **different networks** and routes data using IP addresses.

### Characteristics
- Works at Network Layer (Layer 3)
- Connects LAN to WAN

### Example
- Home Wi-Fi router

---

## 4. Modem
### Description
Converts digital data to analog signals and vice versa.

### Usage
- Connects network to ISP

---

## 5. Access Point (AP)
### Description
Allows wireless devices to connect to a wired network.

### Example
- Wi-Fi access point in offices

---

## 6. Firewall
### Description
Security device that **monitors and controls network traffic**.

### Usage
- Protects internal networks

---

## Device Comparison

| Device | Layer | Purpose |
|-----|------|--------|
| Hub | L1 | Broadcast data |
| Switch | L2 | Forward using MAC |
| Router | L3 | Route using IP |
| Firewall | L3/L4 | Security |

---

## Real-World Example
When you access a website:
- Switch forwards data inside LAN
- Router sends traffic to the internet
- Firewall filters traffic

---

## Interview Points
- Switch is preferred over hub
- Router connects multiple networks
- Firewalls enforce security rules
