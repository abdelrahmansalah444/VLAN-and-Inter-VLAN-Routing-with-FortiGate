# VLAN and Inter-VLAN Routing with FortiGate  
Graduation Project – Digital Egypt Pioneers Initiative (DEPI) – Fortinet Cybersecurity Track

---

## 📌 Project Overview
This project demonstrates the design and implementation of a complete enterprise network using **FortiGate Firewall** and **Cisco Switching**, applying strong security practices for segmentation, access control, and network monitoring.

The network is fully segmented using VLANs, secured through firewall policies, and managed through structured address groups. A Loopback interface was configured to support stable SNMP monitoring and remote management.

---

## 🏗️ Network Architecture
### Key Components:
- **FortiGate Firewall:** Main gateway and security controller  
- **Core Switch (Cisco):** VLAN distribution + trunking  
- **Router (R1):** For external routing and Loopback management  
- **VLANs:** Segmented into departments (HR, Finance, IT, Sales, Marketing, Guests, Servers, Management)

---

## 🔐 Security Features
### Implemented Firewall Policies:
- **Internet Access:** For specific VLANs (Marketing & Guests) using NAT  
- **Server Access:** Only for HR, Finance, and Sales  
- **Guest VLAN Isolation:** Full restriction from internal networks  
- **Admin Access:** IT & Management have full monitoring permissions  
- **Scheduled Server Updates:** Controlled internet access for servers at fixed times  

---

## 📂 Address Groups
Address Groups were created to simplify policy management and enhance visibility:

- **Access Internet**
- **Access Server**
- **Network Maintenance**
- **Protected VLANs**
- **Admins**

This structure reduces the number of policies and improves scalability.

---

## 🌐 Loopback Interface
A Loopback interface was configured on Router R1 to ensure:
- Stable **SNMP Monitoring**
- Consistent **SSH access**
- Reliable **Ping tests**  
FortiGate reaches the Loopback system through a static route.

---

## 🧪 Testing & Validation
The following were tested and verified:
- DHCP functionality per VLAN  
- Inter-VLAN routing  
- Guest network isolation  
- Server access restrictions  
- NAT & firewall rules  
- Connectivity to the Loopback interface  
- Policy logging and traffic monitoring  

---

## 🛠️ Technologies & Tools Used
- **FortiGate Firewall**  
- **Cisco Switches**  
- **Cisco Router**  
- **VLANs & Inter-VLAN Routing**  
- **NAT / Static Routes / Trunking**  
- **SNMP Monitoring**  
- **Address Groups**  
- **Firewall Policies**

---

## 👥 Team Members
- **Ali Ramadan**  
- **Ali Abaza**  
- **Abdelrahman Waleed**  
- **Abdallah Ashraf**  
- **Mohamed Osama**  
- **Ward Ahmed**  
- **Abdelrahman Salah**

---

## 📘 Documentation
All configurations, diagrams, and project documentation are included in this repository.

---

## 🚀 Acknowledgment
A special thank you to the **Digital Egypt Pioneers Initiative (DEPI)** for providing this incredible learning opportunity and hands-on experience in the Fortinet Cybersecurity Track.

---

## 📞 Contact
For inquiries or collaboration:
- **Email:** abdelrahmansalah437@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/abdelrahman--salah  

---
