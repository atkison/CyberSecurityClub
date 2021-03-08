# Network Traffic Analysis

Network traffic analysis begins by understanding the components of network communication. In this context, it will be key to understand the components of network
packets in addition to having the ability to capture, filter, and interpret traffic. Wireshark is very good at packet capture and protocol analysis and is one of the better tools for helping with understanding of network traffic. <br>

Wireshark can be downloaded here: https://www.wireshark.org <br>

The above website contains several tutorials and presentations to help get students up to speed on the use and value of Wireshark. <br>

<i>IP addresses</i> <br>

IP addresses are numeric labels that identify a device (computer, laptop, mobile device) on the Internet or local network. There are two standards for IP addresses: IP Version 4 (IPv4) and IP Version 6 (IPv6). IPv4 is more common, but many are starting to use the new IPv6 standard. Below is a quick overview of IPv4 <br>

In order to create a unique address on the network, IPv4 uses 32 binary bits. Typically, an IPv4 address is expressed using four numbers separated by dots. Each of these numbers are the decimal (base-10) representation for an eight-digit binary (base-2) number, also called an octet. For example: 130.160.43.57 <br>

<i>Ports and Protocols</i> <br>

At the Transport layer, TCP and UDP protocols provide the identification of the network ports. These port numbers determine how incoming network traffic to a system should be directed. Network ports provide the ability for a single system with a signal IP address to handle multiple network services and connections. Each single system can have up to 65535 unique ports and each of these ports can identify a distinct service. <br>

The Internet Corporation for Assigning Names and Numbers (ICANN), which regulates port usage, has established 3 categories for ports: well known ports for common
protocols and services (0-1023), registered ports for specific services (1024-49151), and dynamic ports which are assigned and release based on a session (49152-65535). <br>

Below is a table of common (well-known) ports and associative service name. <br>

<p align="center">
<img width="450px" src="/00_Archive/images/ports.png" alt="Ports"/>
</p>

Below are the header format and definitions for both IPv4 and TCP from https://nmap.org/book/tcpip-ref.html. This site provides a good reference for this
information. <br>

<p align="center">
<img width="550px" height="550px" src="/00_Archive/images/headerformat.png" alt="hf1"/>
<img width="550px" height="550px" src="/00_Archive/images/headerformat2.png" alt="hf2"/>
</p>


