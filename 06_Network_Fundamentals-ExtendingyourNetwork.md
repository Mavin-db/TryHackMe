##Extending a network##
Extending a network involves implementing technologies and configurations to connect private services to the public internet securely,
primarily utilising **port forwarding** and **firewalls**. Without port forwarding, applications and services, such as a web server,
are only available to devices within the same direct network, creating an **intranet**. To make a website accessible to the public
internet, an administrator must implement port forwarding, which is configured at the **router**. This process takes traffic destined
for a public IP address and a specific port and forwards it to a designated computer on the internal network. Complementary to port
forwarding, a **firewall** acts as border security, inspecting packets to determine what traffic is allowed to enter and exit the
network based on factors like source/destination port, address, and protocol (e.g., SSH, UDP, TCP). Firewalls can be categorised as
**stateful**, which inspects the entire connection history but is resource-intensive, or **stateless**, which uses static rules to
inspect individual packets, consuming fewer resources. Firewalls operate at **Layer 3 and Layer 2** of the OSI model.

Another key method for network extension and secure communication is the **Virtual Private Network (VPN)**, a technology that creates
a dedicated, private path or **tunnel** over the internet, allowing devices on separate networks to communicate securely. VPNs enable
the connection of geographically dispersed networks, offering significant benefits such as **privacy** and **anonymity**, often
achieved through encryption. For example, a VPN can connect two separate office networks. VPN technologies include **PPP** (providing
authentication and encryption, but non-routable), **PPTP** (which allows PPP data to travel and leave a network, known for ease of
setup but weak encryption), and **IPsec** (which encrypts data using the existing IP protocol framework, boasting strong encryption
despite being more difficult to set up).

Dedicated networking devices facilitate extension and management. **Routers** connect different networks and perform **routing** by
determining the most optimal path for data delivery, operating at **Layer 3** of the OSI model. **Switches** provide a means for
connecting multiple devices within a single network. While Layer 2 switches forward frames based on MAC addresses, more sophisticated
**Layer 3 switches** can perform some router responsibilities, including routing packets using the IP protocol. Network efficiency,
security, and segregation can be achieved using **VLANs (Virtual Local Area Networks)**, a technology that virtually splits specific
devices on the same switch into separate networks, allowing them to benefit from a single connection (like the internet) while
preventing them from communicating directly with each other if configured with specific rules.
