# Task-3-report
# 🌐 Basic Networking & Wireshark Analysis Lab

## 📌 Objective
The goal of this lab is to understand **basic networking concepts** and use **Wireshark** to capture, filter, and analyze live network traffic. This helps build a foundation for network security, packet analysis, and attack detection.

---

## 🧠 Concepts Covered
- IP Address
- MAC Address
- DNS (Domain Name System)
- TCP & UDP
- Plain-text vs Encrypted Traffic
- Packet Capture & Analysis

---

## 🛠 Tools Used
- Wireshark
- Web Browser (for generating traffic)
- Internet Connection
- Kali Linux / Linux / Windows

---

## 📋 Lab Tasks & Steps

### 1️⃣ Learn Basic Networking Concepts
- **IP Address**: Identifies a device on a network
- **MAC Address**: Unique hardware address of a network interface
- **DNS**: Resolves domain names to IP addresses
- **TCP**: Reliable, connection-oriented protocol
- **UDP**: Fast, connectionless protocol

---

### 2️⃣ Install Wireshark & Capture Live Traffic
1. Install Wireshark
2. Run Wireshark as Administrator/root
3. Select active network interface (Wi-Fi/Ethernet)
4. Start packet capture

---

### 3️⃣ Filter Packets by Protocol
Use the display filter bar in Wireshark:

| Protocol | Filter |
|--------|--------|
| HTTP | `http` |
| DNS | `dns` |
| TCP | `tcp` |

Filtering helps focus on specific traffic types.

---

### 4️⃣ Observe TCP Three-Way Handshake
- Apply filter: `tcp`
- Identify the following packets:
  - **SYN**
  - **SYN-ACK**
  - **ACK**

This confirms how TCP connections are established.

---

### 5️⃣ Identify Plain-Text vs Encrypted Traffic
- **Plain-text protocols**: HTTP, FTP  
  - Data is readable
- **Encrypted protocols**: HTTPS, TLS  
  - Data appears scrambled/unreadable

Use filters:
