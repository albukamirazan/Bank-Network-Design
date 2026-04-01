# Bank-Network-Design
Designing a secure multi-floor banking network using Cisco Packet Tracer with VLAN, DHCP, and ACL configuration
Bank Network Design Using Cisco Packet Tracer


This project presents the design of a secure and organized banking network consisting of five floors, implemented using Cisco Packet Tracer. The goal is to build a fully integrated network that connects all departments and enables smooth communication between employees across all floors.


Project Concept


The bank building is divided into five floors, each assigned to an independent VLAN.

Each floor contains

• 5 computers

• 1 shared printer

• 1 dedicated switch

A multilayer switch is used to connect all floors, and the main servers are placed on the ground floor, functioning as the central routing and service point.

Devices Used


• 5 Switches (one per floor)

• 1 Multilayer Switch

• 1 Server

• Employee computers

• Shared printers

Server Services

The main server (IP: 192.168.80.1) provides:

• DHCP Server — automatic IP assignment

• HTTP/HTTPS Server — secure bank website

• Printer Server — shared printing service


DHCP Configuration

DHCP was enabled for each VLAN with a dedicated pool.

Each device receives

• IP address

• Gateway

• DNS

Verification was done using ipconfig /all.

Connectivity was tested using Ping to ensure successful communication.

ACL Configuration

Access Control Lists were applied on the multilayer switch to:

• Allow internal devices to reach the server

• Block unauthorized external access

• Control communication between VLANs


Connectivity Testing

Ping tests were performed from employee PCs to the server.

Receiving Reply confirmed that the network is functioning correctly.


Project Goal

To build a secure, efficient, and well‑organized network that connects all floors to the central servers, demonstrating proper network design for a financial institution.


Frequently Asked Questions


Q: Why use a multilayer switch instead of a router?

A: It supports VLAN routing and provides faster performance inside the LAN.



Q: What is the purpose of VLANs?

A: They separate the network by floors to reduce congestion and increase security.



Q: Why use DHCP?

A: It assigns IP addresses automatically, simplifies management, and prevents conflicts.



Q: What is the purpose of ACLs?

A: They act as a security filter to control who can access the server.



Q: How did you verify the network is working?

A: By performing Ping
