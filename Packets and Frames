##Packets and frames##
Packets and frames are small units of data that, when combined, form a larger piece of information or a message transmitted across a
network. While both are essential data structures, they exist at different layers of the **OSI Model**. 
A **frame** exists at Layer 2, the Data Link layer, and, importantly, *does not* contain information such as an IP address. 
A **packet** refers to a piece of data that *does* contain **IP addressing information**. The process where a larger message
is broken down, and additional information (like headers) is added as it moves down the layers is known as **encapsulation**.
A helpful analogy for encapsulation is placing an envelope (the frame) inside another envelope (the packet). When the necessary
encapsulating information is removed, the remaining data structure is the frame itself.

Sending data in small pieces as packets is an efficient method of communication because it significantly reduces the likelihood of
**bottlenecking** across the network, which could occur if large messages were sent all at once. For example, when loading an image
from a website, the image is divided into small packets, which are then reconstructed upon reaching the recipient computer. Packets
have specific structures defined by **standards and protocols** (rules). For instance, an Internet Protocol (IP) packet includes
several crucial headers, such as **Time to Live (TTL)** (an expiration timer to prevent network clogs), **Checksum** (which ensures
the integrity of the data), **Source Address** (the sending IP), and **Destination Address** (the receiving IP).

The **Transmission Control Protocol (TCP)**, a connection-based protocol, uses packets with various headers to ensure guaranteed data
receipt. Key headers in a TCP packet include the **Source Port** (randomly chosen by the sender), **Destination Port** (the specific
application or service on the remote host), **Sequence Number** (used for ordering data), and **Acknowledgement Number** (used to
confirm receipt and identify the next expected sequence number). 
TCP uses a defining feature called the **three-way handshake**—involving **SYN**, **SYN-ACK**, and **ACK** messages—to establish a
connection before data is transmitted. By contrast, the **User Datagram Protocol (UDP)** is a **stateless** protocol that does not
require a constant connection or a three-way handshake. UDP packets are simpler, lacking safeguards like the checksum found in TCP, as
speed is prioritised over guaranteed delivery.
