Important concept about port and their numbers
What is a port?
A port is a virtual point where network connections start and end. Ports are managed by a computer's operating system and associated with a specific process or service. Ports allow computers to differentiate between different types of traffic. Emails and webpages, for instance, operate through different ports over the same Internet connection. Most ports are reserved for certain protocols and numbers, for example Hypertext Transfer Protocol (HTTP) messages go to port 80.
How do ports make network connections more efficient?
Data flow to and from a computer over the same network connection so the use of ports helps computers understand what to do with the data they receive from both directions. 
Ports belong to layer 4 level of the OSI model which is the Transport layer therefore a transport protocol such as Transmission Control Protocol (TCP) or User Datagram Protocol (UDP) indicate which port a packet should go to. 
There are around 65,535 port numbers available but not all are commonly used and known. Here I will list a few commonly used port numbers and their protocols.
•	Ports 20 and 21: File Transfer Protocol (FTP). FTP is for transferring files between a client and a server.
•	Port 22: Secure Shell (SSH). SSH is one of many tunneling protocols that create secure network connections.
•	Port 25: Historically, Simple Mail Transfer Protocol (SMTP). SMTP is used for email.
•	Port 53: Domain Name System (DNS). DNS is an essential process for the modern Internet; it matches human-readable domain names to machine-readable IP addresses, enabling users to load websites and applications without memorizing a long list of IP addresses.
•	Port 80: Hypertext Transfer Protocol (HTTP). HTTP is the protocol that makes the World Wide Web possible.
•	Port 123: Network Time Protocol (NTP). NTP allows computer clocks to sync with each other, a process that is essential for encryption.
•	Port 179: Border Gateway Protocol (BGP). BGP is essential for establishing efficient routes between the large networks that make up the Internet (these large networks are called autonomous systems). Autonomous systems use BGP to broadcast which IP addresses they control.
•	Port 443: HTTP Secure (HTTPS). HTTPS is the secure and encrypted version of HTTP. All HTTPS web traffic goes to port 443. Network services that use HTTPS for encryption, such as DNS over HTTPS, also connect at this port.
•	Port 500: Internet Security Association and Key Management Protocol (ISAKMP), which is part of the process of setting up secure IPsec connections.
•	Port 587: Modern, secure SMTP that uses encryption.
•	Port 3389: Remote Desktop Protocol (RDP). RDP enables users to remotely connect to their desktop computers from another device.
If you wish to fully understand more port number and their protocols then research the internet Assigned Numbers Authority (IANA) which maintains the full list of port numbers and protocols assigned worldwide.
[Ports.docx](https://github.com/vadesity/Important-ports-and-their-protocols/files/10300388/Ports.docx)
