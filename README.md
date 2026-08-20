
# 🛡️ Cisco Wireless Network Security Lab

**A hands-on Cisco Packet Tracer project demonstrating wireless network security, MAC address filtering, routing, DNS configuration, and web server connectivity.**

## 📌 Project Overview

This project simulates a small enterprise network using **Cisco Packet Tracer**.

The network includes wireless and wired devices connected through a **WLAN router, edge router, and core switch**, with dedicated DNS and web servers.

## 🎯 Objectives

* 🔐 Configure a secure wireless network
* 🛡️ Implement WPA2-Personal security
* 🔑 Configure AES encryption
* 🚫 Implement MAC address filtering
* 🌐 Configure IPv4 addressing
* 🔀 Configure routing between network segments
* 📡 Connect wireless and wired clients
* 🗂️ Configure a DNS server
* 🌍 Configure an internal web server
* 🧪 Test end-to-end connectivity

## 🖧 Network Components

| Device                         | Purpose                    |
| ------------------------------ | -------------------------- |
| 🛜 WRT300N Wireless Router     | Wireless network access    |
| 🚦 Cisco ISR4321 Edge Router   | Inter-network routing      |
| 🔀 Cisco 2960-24TT Core Switch | Central wired connectivity |
| 🖥️ DNS-Web-Server             | DNS and web services       |
| 🌐 Company-Web-Server          | Hosts the company website  |
| 💻 Employee PCs                | End-user systems           |
| 👨‍💻 Admin PC                 | Network administration     |
| 💻 Laptop                     | Wireless Unauthorized system            |

## 🔐 Wireless Security

The wireless network uses:

* 🔒 **WPA2-Personal**
* 🔑 **AES encryption**
* 🚫 **MAC address filtering**
* ✅ Authorized-device access control

MAC filtering is used to prevent unauthorized devices from connecting to the wireless network.

## 🌐 DNS Configuration

The DNS server is configured with the following record:

**Domain:** `www.company.com`

**IP Address:** `192.168.1.20`

This allows users to access the company web server using a domain name instead of directly entering its IP address.

## 🌍 Web Server

The Company Web Server uses:

**IP Address:** `192.168.1.20`

**Website:** `http://www.company.com`

HTTP service is enabled on the server.

## 🧪 Connectivity Testing

Connectivity was verified using:

`ping 10.0.0.1`

`ping 192.168.1.20`

`ping www.company.com`

Results:

* ✅ Router connectivity
* ✅ Inter-network routing
* ✅ DNS name resolution
* ✅ Web server reachability

## 🛠️ Technologies Used

* 🖥️ Cisco Packet Tracer
* 🌐 IPv4
* 🔀 Routing
* 🛜 Wireless Networking
* 🔐 WPA2-Personal
* 🔑 AES
* 🚫 MAC Address Filtering
* 🗂️ DNS
* 🌍 HTTP
* 🧪 Network Troubleshooting

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* 🖧 Network topology design
* 🔧 Router configuration
* 🛜 Wireless network configuration
* 🔐 Network security
* 🚫 MAC-based access control
* 🗂️ DNS configuration
* 🌍 Web server deployment
* 🔀 Network routing
* 🧪 Troubleshooting and connectivity testing
  
## 📁 Project File

The Cisco Packet Tracer project file included in this repository is:

`Cisco-Wireless-Network-Security-Lab.pkt`

## 👨‍💻 Author

**Akshay M**


---

