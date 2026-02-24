# 🏠 Smart Home IoT Monitoring and Control System  
### Using Cisco Packet Tracer

---

## 📌 Project Overview

This project demonstrates a **Smart Home IoT system** built using **Cisco Packet Tracer**.  

The system simulates how IoT devices inside a home can be:

- Connected through a local network
- Managed using a centralized IoT server
- Accessed remotely through a smartphone
- Secured using authentication (username & password)

It showcases real-time remote monitoring and control over the internet.

---

## 🎯 Objectives

- Design a smart home IoT network architecture
- Configure wireless communication between IoT devices
- Implement centralized device management using an IoT server
- Enable secure remote access via smartphone
- Demonstrate real-world IoT + networking integration

---

## 🏗️ Network Architecture

### 🏠 IoT Devices Included

- Temperature Monitor
- Air Conditioner
- Lights
- Door
- Motion Detector
- Humidifier
- Carbon Dioxide Detector
- Siren
- Water Level Monitor
- Sprinkler
- Garage Door
- Street Lamp
- Solar Panel
- Wind Detector
- Furnace
- Fan

All devices are connected wirelessly to a router.

---

### 📡 Wireless Router

- **Device:** WRT300N
- **IP Address:** `192.168.1.3`
- **Functions:**
  - Default Gateway
  - Wireless Access Point
  - DHCP Provider (optional)

---

### 🖥️ IoT Server

- **Device:** Server-PT
- **IP Address:** `192.168.1.2`
- **Responsibilities:**
  - Hosts IoT Registration Server
  - Stores device configurations
  - Provides web interface
  - Handles user authentication

---

### 🏢 Central Office Server

- **IP Address:** `192.168.1.5`
- Simulates internet/cloud infrastructure.

---

### 📱 Smartphone

- Connects via Cell Tower
- Accesses the IoT server remotely
- Can use:
  - Web Browser → `http://192.168.1.2`
  - IoT Monitoring Application

---

## 🔐 Authentication

To access the system:

- **Username:** `Home`
- **Password:** `secret`

The server validates credentials before allowing device control.

This demonstrates:

- Access control
- Secure login mechanism
- Basic IoT security implementation

---

## 🌐 Remote Access Workflow

### Step 1: Internet Connection
Smartphone → Cell Tower → Central Office Server

### Step 2: Server Request
User enters:
http://192.168.1.2

Request path:
Smartphone → Internet → Wireless Router → IoT Server

### Step 3: Authentication
User enters credentials  
Server verifies login details  

### Step 4: Control Dashboard
After successful login, the user can:

- Turn lights ON/OFF
- Lock/Unlock doors
- Monitor temperature
- Activate sprinkler
- Monitor CO2 levels
- Control garage door
- Monitor water level
- Control appliances

All actions occur in real-time.

---

## 📚 Networking Concepts Used

- TCP/IP Protocol Suite
- HTTP Protocol
- Private IP Addressing (192.168.1.0/24)
- Wireless Networking (802.11)
- Routing
- DHCP
- Client-Server Architecture
- IoT Architecture

---

## 🧠 Real-World Applications

- Smart Homes
- Industrial Automation
- Smart Cities
- Remote Monitoring Systems
- Energy Management Systems

---

## 🚀 Future Enhancements

- HTTPS implementation
- VLAN separation (IoT network isolation)
- Firewall configuration
- Cloud integration
- AI-based automation rules
- Mobile app interface enhancement

---

## 🛠️ Tools Used

- Cisco Packet Tracer
- IoT Devices (Simulated)
- Server-PT
- WRT300N Wireless Router
- Smartphone-PT
- 2950 Switches

---

## 👨‍💻 Authors

Antony Joy Ukken  
Computer Networks Project (CIA - 3)

---
