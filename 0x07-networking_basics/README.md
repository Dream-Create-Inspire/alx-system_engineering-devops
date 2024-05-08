#0x07. Networking basics

##Learning Objectives

##OSI Model

###What it is?
The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and describe how different networking protocols interact within a networked environment. It consists of seven layers, each with its specific function:
###How many layers it has?
Physical Layer: Deals with the physical connection between devices and transmission of raw data over a physical medium.
Data Link Layer: Handles the reliable transmission of data frames between nodes over a physical connection. It also manages error detection and correction.
Network Layer: Responsible for routing and forwarding data packets between nodes across different networks. It provides logical addressing and determines the best path for data to travel.
Transport Layer: Ensures reliable data delivery between nodes by providing mechanisms for error detection, flow control, and retransmission of lost packets.
Session Layer: Establishes, maintains, and terminates connections between applications on different devices. It manages sessions and synchronization between communicating applications.
Presentation Layer: Handles data translation, encryption, and compression to ensure that data sent by one application can be understood by another.
Application Layer: Provides network services directly to end-users and applications, such as email, file transfer, and web browsing.

##What is a LAN
A LAN (Local Area Network) is a network that covers a small geographical area, typically within a single building or campus. It is used to connect devices like computers, printers, and servers, allowing them to communicate and share resources.


##What is a WAN
A WAN (Wide Area Network) is a network that spans a large geographical area, often connecting multiple LANs or other networks across cities, countries, or continents. It enables long-distance communication and data exchange between distant locations.
##What is the Internet
The Internet is a global network of interconnected computers and devices that use the TCP/IP protocol suite to communicate. It allows users to access a vast array of information and services, including websites, email, and file sharing.
###What is an IP address?
An IP address (Internet Protocol address) is a numerical label assigned to each device connected to a network that uses the Internet Protocol for communication. It serves as a unique identifier for the device within the network.
###What are the 2 types of IP address?
There are two types of IP addresses: IPv4 (Internet Protocol version 4) and IPv6 (Internet Protocol version 6). IPv4 addresses are 32 bits long and are written in the form of four decimal numbers separated by periods (e.g., 192.168.1.1). IPv6 addresses are 128 bits long and are represented as eight groups of hexadecimal digits separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
###What is localhost
"Localhost" refers to the loopback network interface of a device, typically assigned the IP address 127.0.0.1. It allows a device to communicate with itself, enabling local testing and development of network services.
###What is a subnet
A subnet (subnetwork) is a portion of a larger network that has been divided into smaller, more manageable segments. Subnetting allows for better network management, security, and optimization of network resources.
Why IPv6 was created
IPv6 was created to address the limitations of IPv4, primarily the exhaustion of available IPv4 addresses due to the rapid growth of the Internet. IPv6 provides a much larger address space, improved security features, and enhanced support for mobile devices and emerging technologies.


##TCP/UDP
###What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are the two main transport layer protocols used for data transfer in IP networks. 
###What is the main difference between TCP and UDP
TCP provides reliable, connection-oriented communication with error detection, flow control, and retransmission of lost packets. UDP, on the other hand, is connectionless and provides best-effort delivery without error correction or retransmission.
###What is a port
A port is a communication endpoint in an operating system that is used to uniquely identify a specific process or service. Ports are associated with specific protocols, such as TCP or UDP, and are used to facilitate communication between devices.
###Memorize SSH, HTTP and HTTPS port numbers
The commonly used port numbers for SSH (Secure Shell), HTTP (Hypertext Transfer Protocol), and HTTPS (HTTP Secure) are 22, 80, and 443, respectively.
###What tool/protocol is often used to check if a device is connected to a network
Ping is a commonly used tool and protocol for checking the connectivity between devices on a network. It sends ICMP (Internet Control Message Protocol) echo request packets to a specific IP address and waits for a response, indicating whether the target device is reachable.

##Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
##Requirements
General
Allowed editors: vi, vim, emacs
All your Bash script files will be interpreted on Ubuntu 20.04 LTS
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
All your Bash script files must be executable
Your Bash script must pass shellcheck without any error
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what is the script doing
