Sun Oct 12 06:54:22 PM AEST 2025
##What is Networking
Networking fundamentally refers to things that are interconnected, extending beyond computing to include real-world systems like a
city's public transportation, the national power grid for electricity, or even the postal system. More specifically in computing,
networking applies this concept to technological devices, where a network can consist of anywhere from two to billions of devices,
including laptops, phones, security cameras, and traffic lights. Networks are deeply integrated into modern life for tasks such as
delivering electricity or gathering weather data, making the concept essential to understand in cybersecurity.

The **internet** itself is defined as one gigantic network composed of many smaller networks joined together. These small, localised
systems are called **private networks** (such as a home or business network), while the networks connecting them are referred to as
**public networks** or simply the internet. The first documentation of a network was the **ARPANET** project in the late 1960s, funded
by the United States Department of Defense, but the internet as we know it was invented in 1990 by **Tim Berners-Lee** with the
creation of the **World Wide Web (WWW)**.

To communicate and maintain order, devices must be both identifying and identifiable on a network. They are identified primarily using two methods:

1.  **IP Address (Internet Protocol address):** This identifies a host on a network for a period of time, similar to a street address,
and can change. IPv4 addresses are typically split into four numerical sections called **octets**, each ranging from 0 to 255. Devices
use either a **public IP address** (for communicating on the internet) or a **private IP address** (for communicating amongst other
devices on the internal network). Because the 4.29 billion available IPv4 addresses are becoming scarce due to the huge number of
connected devices, **IPv6** was developed, which supports 340 trillion-plus addresses and uses more efficient methodologies.

2. **MAC Address (Media Access Control address):** This is a unique, physical identifier assigned to a network interface (like a Wi-Fi
card or ethernet port) at the factory. It is referred to as "burnt in" and is theoretically globally unique. A MAC address is a 
16-character hexadecimal number. While unique, a MAC address can be **spoofed** (faked) to pretend to be another device, which is
sometimes used to bypass poorly implemented security measures like guest Wi-Fi controls.

A fundamental tool used to test network connectivity is **Ping**, which utilises **ICMP (Internet Control Message Protocol)** packets.
Ping measures the time taken for ICMP echo packets to travel between devices, helping to determine if a connection exists or is
reliable.
