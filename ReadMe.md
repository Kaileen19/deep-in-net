Deep-in-Net

I have added all the answers in this ReadMe file.

You will need to download Cisco Packet Tracer.

Exercise 1

![alt text](img/image-1.png)

What is RJ-45 cable?

An RJ-45 cable is a type of network cable used for Ethernet connections. It has a rectangular connector with 8 pins and is used to connect devices like computers, routers, and switches for wired data transmission in local area networks (LANs). It is the standard cable for most wired networking setups.

Understand what is the difference between straight through and crossover RJ-45 cables.

1. Straight-through Cable:

   Wires: The wires are arranged the same on both ends.
   Use: It is used to connect different devices, like a computer to a router or a switch to a router.

2. Crossover Cable:
   (Also used for our example image-1.png)
   Wires: The wires are arranged differently on each end (two pairs are swapped).
   Use: It is used to connect similar devices, like two computers or two switches directly to each other.

In summary:

    Straight-through = different devices (e.g., computer to router).
    Crossover = similar devices (e.g., computer to computer).

Exercise 2
![alt text](img/image.png)

Understand the function of a switch and a hub, how they operate and their role in networking.

Switch:

    Function: A switch connects multiple devices in a network and sends data only to the **device it is meant for**.
    How it works: It uses **MAC addresses to identify devices**. When it gets data, it checks the destination and sends it only to the correct device, improving network efficiency.
    Role: Switches **reduce network traffic and help devices communicate faster and more securely**.
    OSI 2 - (Data Link Layer) — More intelligent, reduces traffic.

Hub:

    Function: A hub also connects multiple devices, but it sends data to **all devices**, not just the intended one.
    How it works: It **doesn't check where the data should go; it broadcasts it to everyone**, which can lead to network congestion.
    Role: Hubs are **simpler but less efficient** and can slow down the network.
    OSI 1 - (Physical Layer) — Simple, broadcasts data to all devices.

Summary:

    Switch = Sends data to the correct device, reduces traffic.
    Hub = Sends data to all devices, increases traffic.

Exercise 3

![alt text](img/screenrecord.gif)

    Server and Its Purpose in Networking: A server is a computer or system that provides services, data, or resources to other computers (clients) over a network. Servers can offer things like web pages, files, emails, or even games.

    DHCP (Dynamic Host Configuration Protocol): DHCP is a protocol that automatically assigns IP addresses to devices on a network. Instead of manually configuring each device with an IP address, the DHCP server gives each device an IP address when it joins the network.

    DNS (Domain Name System): DNS is like the phonebook of the internet. It translates human-friendly domain names (like www.example.com) into IP addresses (like 192.168.1.1) that computers use to locate each other on a network.

    HTTP (Hypertext Transfer Protocol): HTTP is used for transferring web pages over the internet. When you visit a website, your browser uses HTTP to request and receive web pages from a web server.

    HTTPS (Hypertext Transfer Protocol Secure): HTTPS is a secure version of HTTP. It uses encryption to protect the data being sent between your browser and the server, ensuring privacy and security. It’s often used for online transactions.

    FTP (File Transfer Protocol): FTP is a protocol used to transfer files over a network. It allows users to upload or download files to/from a server, often used for website maintenance or file sharing.

    TCP and UDP Communication:

    TCP (Transmission Control Protocol) is reliable and ensures that data is delivered in order and without errors. It’s used for things like web browsing and email.
    UDP (User Datagram Protocol) is faster but less reliable. It doesn’t guarantee delivery or order, making it suitable for things like video streaming or gaming.

    OSI Model Layer for TCP and UDP: TCP and UDP both operate at the Transport Layer (Layer 4) of the OSI model. They handle end-to-end communication and data flow between devices.

    Port in Networking: A port is like a door or entry point that allows different types of data to flow into and out of a computer or device. Each service or protocol usually uses a specific port number.

    Ports and OSI Layers for Protocols:

    HTTP: Port 80, operates at Application Layer (Layer 7).
    HTTPS: Port 443, operates at Application Layer (Layer 7).
    FTP: Port 21, operates at Application Layer (Layer 7).
    TCP/UDP: Operates at Transport Layer (Layer 4).

    Different Types of DNS Records:

    A Record: Maps a domain to an IP address.
    MX Record: Specifies mail servers for a domain.
    CNAME Record: Maps a domain to another domain (alias).
    NS Record: Defines authoritative name servers for a domain.
    PTR Record: Used for reverse DNS lookups (IP to domain).

Ex.4

![alt text](img/image-2.png)

Ex.5

![alt text](img/image-3.png)

Ex.6
![alt text](img/image-4.png)

Ex.7
![alt text](img/image-5.png)

Ex.8
![alt text](img/image-6.png)
