# pfSense-Firewall-Lab-Setup

## 📦 What This Lab Covers
- Deploying pfSense firewall on VirtualBox
- Creating WAN + LAN network interfaces
- Routing all Kali Linux traffic through pfSense
- Accessing and configuring the pfSense Web GUI
- Creating and testing firewall rules
- Validating internet access and traffic filtering

## 📡 Network Diagram

I started by mapping out the network topology to understand how traffic would flow through the virtual environment.
My goal was to keep the design simple: pfSense acts as the firewall and gateway, while Kali Linux sits on the internal network behind it.

This helped me clearly visualize the separation between the external network (WAN), the internal network (LAN), and how Kali would route all traffic through pfSense.
