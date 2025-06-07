# UDP-Flooder
UDP Flooder written in python

🛠️ NetworkKiller v3.0 – High-Throughput Packet Generation and Analysis GUI Tool
Overview:
NetworkKiller v3.0 is a Python-based GUI application designed for generating and analyzing high volumes of network packets using both raw sockets and Scapy. The tool supports two primary modes—UDP flood and SYN flood—intended for stress testing and network simulation in controlled or research environments.

Key Features:

Real IP Spoofing using Scapy for crafting custom IP headers.

Multiple Attack Modes: Selectable between UDP and SYN-based packet generation.

Thread Optimization: Supports launching up to 2000 concurrent threads for load simulation.

Dynamic Target Resolution: Automatically resolves domain names to IPs.

Live Packet Analytics: Real-time stats including total packets sent, failed packets, and packets per second (PPS).

Modern GUI Interface: Built with Tkinter and styled with a dark "military" aesthetic.

Logging Console: Embedded text log for packet operations and status updates.

Technical Highlights:

Written in Python using tkinter for GUI, socket for standard UDP sending, and scapy for raw packet crafting.

Utilizes multithreading to maximize throughput.

Allows customizable settings for target, port, thread count, and packet size.

Spoofed packets are constructed using randomized IPs for the source address field (when enabled).

Use Cases (when used responsibly):

Network performance/load testing in a controlled lab environment.

Packet-level simulation for research or academic purposes.

Educational tool for learning about packet crafting and network traffic behaviors.

