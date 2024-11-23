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
