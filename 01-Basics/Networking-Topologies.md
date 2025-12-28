# Network Topologies

## What is Network Topology?
Network topology refers to the **physical or logical arrangement** of devices (nodes) in a network and how they are connected.

---

## 1. Bus Topology
### Description
All devices are connected to a **single communication cable (backbone)**.

### Advantages
- Easy to install
- Low cost

### Disadvantages
- Backbone failure brings down entire network
- Performance degrades with more devices

### Example
- Early Ethernet networks

---

## 2. Star Topology
### Description
All devices are connected to a **central device (switch or hub)**.

### Advantages
- Easy to manage and troubleshoot
- Failure of one device doesn’t affect others

### Disadvantages
- Central device failure affects entire network

### Example
- Modern office and home networks

---

## 3. Ring Topology
### Description
Devices are connected in a **circular fashion**, and data travels in one direction.

### Advantages
- Predictable performance

### Disadvantages
- Failure of one device breaks the ring
- Difficult to troubleshoot

### Example
- Token Ring networks (older systems)

---

## 4. Mesh Topology
### Description
Each device is connected to **multiple other devices**.

### Advantages
- High reliability
- No single point of failure

### Disadvantages
- Expensive
- Complex to maintain

### Example
- Data centers
- Wireless mesh networks

---

## 5. Hybrid Topology
### Description
Combination of two or more topologies.

### Example
- Star + Mesh in enterprise networks

---

## Comparison Table

| Topology | Cost | Reliability | Usage |
|-------|------|------------|------|
| Bus | Low | Low | Rare |
| Star | Medium | High | Common |
| Ring | Medium | Medium | Rare |
| Mesh | High | Very High | Data centers |

---

## Real-World Usage
- Star → Offices, homes
- Mesh → Cloud & data centers

---

## Interview Points
- Star topology is most commonly used
- Mesh provides redundancy
- Switch-based star topology improves performance
