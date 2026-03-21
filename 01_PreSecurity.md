# TryHackMe: Pre-Security Pathway
**A Learner’s Perspective from a Web Developer and Digital Technology Educator**

*I first started this pathway way in OCtober 2025 whilst i was still in the ast part of term 4 ( the most busiest for a Music teacher ) I became consistent when school finished on the 12th of DEcember 2025.*

As a professional with a background in web development and experience teaching Digital Technology, I approached the TryHackMe Pre-Security pathway not just to learn the "how-to" of hacking, but to understand the foundational "why" behind system vulnerabilities. Coming from a Linux environment where I frequently write Bash scripts, I found this pathway to be an excellent bridge between building applications and protecting them.

---

## 01: Introduction to Cyber Security

### 01_Offensive_Security_Intro
This was a fantastic "hook" for the pathway. The FakeBank exercise reminded me of my early web dev days, finding hidden directories is something we often do during debugging, but using `dirb` to do it programmatically for a "hack" provides a completely different perspective on URL structure and security through obscurity.

### 02_Defensive_Security_Intro
As an educator, I appreciated the clear distinction between the Red and Blue teams. The introduction to SOC and Digital Forensics resonated with my administrative side; it’s one thing to build a server, but another entirely to monitor system memory for malicious code that never touches the disk.

### 03_Careers_in_Cyber
This module is a goldmine for students. It breaks down roles like "Penetration Tester" and "Security Engineer" into actionable learning paths. It highlights how my existing skills in low-level languages and system architecture can pivot into high-demand security roles.

---

## 02: Network Fundamentals

### 01_What is Networking?
A solid refresher. Even for someone who deals with IP addresses daily, the distinction between private and public networks and the history of the WWW (shoutout to Tim Berners-Lee) is essential context for understanding how the global "network of networks" actually functions.

### 02_Intro to LAN
The visual breakdown of Star, Bus, and Ring topologies is exactly how I teach this in class. Understanding the physical layer is crucial when you're trying to figure out where a network-based attack might originate.

### 03_OSI_Model
The OSI Model is something I had forgot about, but TryHackMe makes it tangible. As a developer, I usually live at Layer 7 (Application), but seeing how data is encapsulated down to Layer 1 (Physical) helps me understand why certain packet-level attacks work.

### 04_Packets_and_Frames
The "Three-Way Handshake" (SYN, SYN/ACK, ACK) is a core concept I’ve used in my Linux troubleshooting. This module perfectly illustrates how the transport layer ensures data integrity, a critical concept for anyone building reliable web services.

### 05_Extending_your_Network
The practical simulator for port forwarding and firewalls was excellent. In my home lab, I’ve done this manually, but seeing the step-by-step logic of how a firewall inspects packets at Layers 3 and 4 helps solidify the "Security Mindset."

---

## 03: How the Web Works

### 01_DNS in Detail
This module’s breakdown of TLDs, Authoritative servers, and record types (A, AAAA, MX) is the most concise explanation I’ve seen. It’s essential for understanding how attackers might use DNS for spoofing or redirection.

### 02_HTTP_in_Detail
This felt like home. I’m familiar with GET, POST, and Status Codes. However, looking at headers like `User-Agent` and `Set-Cookie` through a security lens, specifically for session hijacking or browser identification, was a valuable shift in perspective.

Check out my cURL repo for more. 

### 03_How_Websites_Work
The sections on HTML and JS injection were particularly relevant. I’ve built many forms, but this module reinforced the "Golden Rule" of development: **Never trust user input.** The practical on Sensitive Data Exposure (finding passwords in comments) is a huge mistake. I've seen even experienced developers leave sensitive info on the page.

### 04_Putting_it_all_together
This summary module on Load Balancers, CDNs, and WAFs explains the "scale" of the modern web. Understanding that a WAF sits between the request and the server is a key architectural takeaway.

---

## 04: Computer Fundamentals

### 01_Inside_a_Computer
The analogy of the computer as a "castle" is brilliant for teaching. Understanding that the CPU is the "brain" and RAM is "short-term memory" provides a physical grounding for abstract concepts like buffer overflows or memory corruption later on.

### 02_Computer_Types
In a world of IoT and smart fridges, this module reminds us that "computers" are everywhere. The distinction between "Embedded" and "IoT" (connectivity) is a vital nuance in the modern tech landscape.

### 03_Client-Server-Basics
The pizza delivery analogy for the client-server model is one I will definitely be stealing for my classroom. It simplifies the request-response cycle and the role of ports in a way that anyone can grasp.

### 04_Virtualisation_Basics
This is where my Linux experience really kicked in. Having used Type 2 hypervisors for testing, I appreciated the breakdown of VMs vs. Containers. For a developer, understanding that containers share the host kernel is essential for modern DevOps and security.

### 05_Cloud_Computing_Fundamentals
Cloud is no longer optional. The IaaS, PaaS, and SaaS models are concepts I looked at in my web dev diploma. The hands-on with a simulated AWS console was a great way to show how "Scalability" and "Pay-as-you-go" actually look in practice.

---

## 05: Operating System Basics

### 01_Operating_Systems-Introduction
The "Invisible Manager" analogy perfectly describes the OS. The distinction between Kernel Space and User Space is perhaps the most important security concept in this section. It explains why some things require `sudo` or Administrator privileges.

### 02_Windows_Basics
Even as a Linux enthusiast, I recognise Windows is the enterprise standard. Navigating the Task Manager and Windows Security settings is foundational for any Blue Team member investigating a workstation breach.

### 03_Linux_CLI_Basics
This felt like second nature, but I loved the "Mission" approach. Using `pwd`, `ls`, and `find` to navigate the system is the bread and butter of my daily work. For a beginner, this is the most empowering module in the path.

### 04_Windows_CLI_Basics
Translating my Linux CLI knowledge to CMD was interesting. `dir /s` is a powerful tool, and understanding how to gather `ipconfig` and `systeminfo` is critical when you’re "living off the land" in a Windows environment.

### 05_Operating System Security
The "CIA Triad" (Confidentiality, Integrity, Availability) is the heart of security. The practical at the end, cracking a weak password via SSH and escalating to root, is a classic exercise that never fails to show the danger of "password123"

---

## 06: Software Basics

### 01_Data_Representation
Understanding Binary and Hexadecimal is fundamental for low-level security. I’ve used hex for colours, but seeing how 16 million colours are just 3 bytes (24 bits) makes the math of computing much more real.

### 02_Data_Encoding
ASCII vs. Unicode is a common pain point in web dev. This module explains why that happens. Understanding UTF-8's dynamic byte length is a cool bit of engineering that most of us take for granted.

### 03_Python-Simple_Demo
Python is the language of security. Having taught simple programming, I found this Guess the Number demo to be a great way to show how variables, `if` statements, and `while` loops create logic.

### 04_JavaScript-Simple_Demo
I use JS most days. Seeing it run in Node.js for a simple CLI game illustrates its versatility. The subtle differences between `let` and `const` are important "good practice" habits for any student.

### 05_Database-SQL_Basics
SQL is the language of data. The café order example is a perfect way to introduce `SELECT`, `WHERE`, and `ORDER BY`. Knowing how to query a database is step one in understanding (and preventing) SQL Injection. I have my own database for documenting my daily routine. Doing it daily has really helped endure i know what I am doing.

---

## 07: Attacks and Defenses

### 01_The_CIA_Triad
A great look into the triad. The "Security Mindset" of asking "Was data modified?" (Integrity) or "Was it available?" (Availability) is what separates a technician from a security professional. The CIA triad has been mentioned in every Cyber security course I have looked at, so it is extremely important to understand.

### 02_Cryptography_Concepts
Symmetric vs. Asymmetric encryption can be confusing, but the "lockbox" vs. "mailbox" analogies are brilliant. Understanding that HTTPS uses a hybrid approach (asymmetric for the handshake, symmetric for the data) is a "lightbulb moment" for many. After doing this room I created my own lab to decrypt codes and unlock password protected zip files. 

### 03_Becoming_A_Hacker
This was the culmination of the path. Using `gobuster` and `hydra` to chain a hidden directory vulnerability with a weak password vulnerability is a classic Red Team move. It turns theory into practice.

### 04_Become_A_Defender
The final module balances the scales. Mapping a "city" of infrastructure and applying defenses like firewalls and antivirus shows that security is a layered game of "Prevention, Detection, and Mitigation."

---

### Final Thoughts
The TryHackMe Pre-Security pathway is an essential foundation. Whether you are a student, a teacher, or a developer, it takes the "magic" out of technology and replaces it with structured, logical understanding. It has significantly improved my ability to explain security concepts and has made me a more security-conscious developer. Now to do the SEC0 certification. 
