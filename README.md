# WanDesignForMultipleOfficeConnectivity
Computer Networks Project

Team Members:
1. Shubham Shreshth - 1DS19CS156
2. Shamsher Tiwari - 1DS19CS147
3. Satyam Singhal - 1DS19CS144
4. Rithik Mrinal - 1DS18CS104

PROJECT ABSTRACT: 

An organization with many remote offices and one main office. The organization designed a WAN network through which both the remote offices have dedicated leased lines to the main office. The speed of the leased line links is 64 Kbps. The organization uses Cisco routers and switches. The necessary topology and configurations are identified on the routers for the computers in the different offices to access each other. A lab is set up with actual Cisco equipment to simulate topology along with the working configurations.

INTRODUCTION:

-	WAN is the sum of the configurations and design of the interconnections between the data center and corporate headquarters and the rest of the enterprise. The office remote sites can consist of campus environments as well as small offices, revenue gateways (such as a storefront or branch sales office), and other remote locations.
-	Office WAN is often designed to provide dedicated interconnection with partners, home-based workers, and other support resources. This is the key to the solution as it provides the backbone over which most office traffic travels. 
-	Coming to the implementation, we have made a WAN for offices located in different geographical regions namely India, US and UK with the US office acting as a central repository for the data storage and having servers to respond to the request. and India also has a server for the offices located in the India.
-	Each server, router and switches are configured using CLI to provide necessary configurations so that they can serve in the WAN.
-	In the end, the offices can communicate remotely using WAN.

-	Devices used in this project are:
1.	Routers
2.	Switches
3.	Cables
4.	Servers
5.	PC’s

-	Servers used in this project are: 

1.	FTP Server and TFTP Server: 
-	FTP (File Transfer Protocol) is a standard communication protocol used for the transfer of computer files from a server to a client on a computer network. 
-	TFTP Server is used for simple file transfer (typically for boot-loading remote devices). Trivial File Transfer Protocol (TFTP) is a simple protocol for exchanging files between two TCP/IP machines. The TFTP Server can also be used to upload HTML pages onto the HTTP Server or to download log files to a remote PC.

2.	NTP Server or TIME Server:
-	NTP is an internet protocol that's used to synchronize the clocks on computer networks to within a few milliseconds of universal coordinated time (UTC). It enables devices to request and receive UTC from a server that, in turn, receives precise time from an atomic clock.

3.	Syslog Server or LOG Server:
-	System Logging Protocol (Syslog) is a way network device can use a standard message format to communicate with a logging server.

4.	HTTP/HTTPS:
-	Hypertext Transfer Protocol (HTTP) is an application-layer protocol for transmitting hypermedia documents, such as HTML. It was designed for communication between web browsers and web servers, but it can also be used for other purposes.
-	Hypertext Transfer Protocol Secure (https) is a combination of the Hypertext Transfer Protocol (HTTP) with the Secure Socket Layer (SSL)/Transport Layer Security (TLS) protocol. TLS is an authentication and security protocol widely implemented in browsers and Web servers.

5.	DNS Server:
-	The Domain Name System (DNS) Server is a server that is specifically used for matching website hostnames (like example.com) to their corresponding Internet Protocol or IP addresses. The DNS server contains a database of public IP addresses and their corresponding domain names.

6.	DHCP Server:
-	A DHCP Server is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. It relies on the standard protocol known as Dynamic Host Configuration Protocol or DHCP to respond to broadcast queries by clients.

PLATFORM USED (H/W & S/W TOOLS TO BE USED): Cisco Packet Tracer
