# Home-IOT-Project
Home IOT Project Using Cisco Packet Tracer
# 🏠 Home IoT Network Simulation using Cisco Packet Tracer

## 📖 Project Overview

This project demonstrates a Smart Home Internet of Things (IoT) network designed and simulated using Cisco Packet Tracer. The network connects multiple smart devices to a home wireless gateway and enables communication with a centralized IoT server through a routed network.

The purpose of this project is to understand IoT architecture, wireless networking, IP addressing, and remote device management in a smart home environment.

---

## 🎯 Objectives

* Design a Smart Home IoT network.
* Connect IoT devices through a wireless home gateway.
* Configure IP addressing and network connectivity.
* Implement communication between IoT devices and an IoT server.
* Demonstrate remote monitoring and automation concepts.

---

## 🖥️ Network Topology

### Devices Used

#### Home Network

* Home Wireless Gateway
* PC
* Laptop
* Smartphone
* Smart Fan
* Smart Air Conditioner
* Smart Light
* Smart Door
* Humiture (Temperature & Humidity) Monitor

#### Infrastructure Network

* Cisco 2901 Router
* Cisco 2960 Switch
* IoT Server

---

## 🌐 IP Addressing

| Device/Network                 | IP Address  |
| ------------------------------ | ----------- |
| Home Gateway                   | 10.1.1.2/24 |
| Router Interface (Home Side)   | 10.1.1.1/24 |
| Router Interface (Server Side) | 10.1.2.1/24 |
| IoT Server                     | 10.1.2.2/24 |

---

## ⚙️ Configuration Summary

### Home Wireless Gateway

* Configured as the central IoT controller.
* Provides wireless connectivity to IoT devices.
* Manages communication between smart devices.

### Router Configuration

* Connected Home Network and IoT Server Network.
* Configured interfaces with appropriate IP addresses.
* Enabled routing between subnets.

### IoT Server

* Configured to register and manage IoT devices.
* Allows centralized monitoring and control.

### Smart Devices

* Connected wirelessly to the Home Gateway.
* Registered with the IoT Server.
* Capable of remote monitoring and automation.

---

## 📋 Features Demonstrated

* Smart Home Automation
* Wireless IoT Connectivity
* Device Registration
* Remote Monitoring
* Network Segmentation
* Inter-Network Communication
* Cisco Packet Tracer IoT Simulation

---

## 🛠️ Tools Used

* Cisco Packet Tracer
* Cisco 2901 Router
* Cisco 2960 Switch
* IoT Devices
* Wireless Networking

---

## 📂 Project Files

```text
Home-IoT-Project/
│
├── Home_IOT.pkt
├── topology-screenshot.png
└── README.md
```

---

## 🚀 Learning Outcomes

Through this project, I learned:

* IoT network architecture
* Wireless device integration
* Router and switch configuration
* IP addressing and subnetting
* Smart device communication
* Cisco Packet Tracer IoT implementation

---

## 👨‍💻 Author

Velmurugan S

BCA Graduate | Networking Enthusiast | CCNA Learner | Future Network & Cloud Engineer

---

## ⭐ Future Enhancements

* DHCP Integration
* DNS Configuration
* VLAN Segmentation
* IoT Security Implementation
* Remote Internet Access
* Cloud-Based IoT Management
