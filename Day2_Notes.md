# 🌐 Networking Basics – IP, IPv4, IPv6 & DNS

## 📌 Fundamental Concepts

- **IP Address:** A numeric identifier assigned to each device on a network.
- Used for communication between devices over the internet.
- Every IP address has:
  - **Network Address** → Identifies the network
  - **Host Address** → Identifies the device

- Computers understand IP addresses in **binary (0s and 1s)**.

---

## 🌍 IPv4 (Internet Protocol Version 4)

- **32-bit address**
- Written in **decimal format**
- Example: `192.168.1.1`

### 🔹 Key Points:
- Divided into **4 octets**
- Each octet ranges from **0–255**
- Total addresses: **~4.3 billion**

### 🔹 Binary Representation:
Each octet has 8 bits:



---

## 🌐 IPv6 (Internet Protocol Version 6)

- **128-bit address**
- Written in **hexadecimal format**
- Example: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`

### 🔹 Key Points:
- 8 groups of 16 bits
- Separated by `:`
- Uses numbers + letters (A–F)

### 🔹 Capacity:
- ~**340 undecillion addresses**
- Solves IPv4 exhaustion problem

### 🔹 Hex Values:
A = 10
B = 11
C = 12
D = 13
E = 14
F = 15


---

## 🔄 IPv4 vs IPv6

| Feature | IPv4 | IPv6 |
|--------|------|------|
| Address Length | 32-bit | 128-bit |
| Format | Decimal | Hexadecimal |
| Separator | . | : |
| Total Addresses | ~4.3 Billion | ~340 Undecillion |

---

## 🌐 DNS (Domain Name System)

- DNS = **Internet Phonebook**
- Converts **domain names → IP addresses**

Example: google.com → 142.250.183.14


---

## 🔍 DNS Lookup Process

1. **Resolver (ISP)**
2. **Root Server**
3. **TLD Server (.com, .org)**
4. **Authoritative Server**

---

## ⚙️ How It Works

- User enters domain name
- Request goes to resolver
- Resolver checks cache
- If not found → queries hierarchy
- Returns IP address
- Browser loads website

---

## ⚡ DNS Caching

To improve speed, DNS stores data in:

- Browser cache
- OS cache
- ISP cache

---

## 🎯 Interview Questions & Answers

### ❓ What is DNS?
DNS converts domain names into IP addresses.

---

### ❓ Why is DNS needed?
Humans can't remember IP addresses, so DNS makes it easier.

---

### ❓ DNS hierarchy?
- Resolver
- Root Server
- TLD Server
- Authoritative Server

---

### ❓ What is caching in DNS?
Storing IP addresses to avoid repeated lookup.

---

## 💡 My Understanding

- Network = devices connected to share data  
- Internet = global network of networks  
- IPv4 is limited → IPv6 solves scalability  
- DNS makes internet user-friendly  

---

## 🚀 Key Takeaways

- IP = identity of device
- IPv4 = limited, IPv6 = future
- DNS = backbone of internet navigation