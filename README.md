# Network Scanning using Nmap 

Name: Rory Stiff


Purpose of Project: In this project I am putting my Nmap skills to the test by scanning devices on my network.
In this project I will be demonstraiting how Nmap can a very powerful tool for Cyber Security Profesionals and how
it can be used in malicious ways used by hackers. 

![image](https://github.com/user-attachments/assets/1ff3c27a-535d-4e94-ab37-0b805ecdba7f)



Tools that Im using:
- The virtual machine im using is Virtual Box
- I am using a ALFA which is a Long-Range USB adapter so I can be connected to the internet in Kali
- Kali Linux
- Nmap


Topics covered:
-
- Ping Scan
- TCP vs UDP scans
- SYN can
- Service Version Detection
- OS Detetction
  




Ping Scan:
-

what is a ping scan useful for?

A ping scan in Nmap identifies all of the ip addresses that are currentley online
without sending any packets to these hosts.  This is useful for penetration testers and system administartors to
determine if hosts are online or to perform light reconnassance of a target network.


How to do a ping scan:

### Nmap Command Example

To scan the network for devices using Nmap, use the following command:



![image](https://github.com/user-attachments/assets/add6868f-e0e2-4ff4-9a84-c3b210626610)

- After doing that command you can then see how many ip addreses are on your network and how many devices are connected to it.

![image](https://github.com/user-attachments/assets/9c259d35-6c6c-40c5-a289-00e66e18240a)

- The picture above shows how many ip addreses there are as well as how many devices are connected to the Network.


TCP Vs. UDP Scans
-

What is TCP?  TCP(Transmission Control Protocol) is a communications standard thats enables
devices and applications to exchange messages over a network. The TCP Protocol is apart of the TCP/ip protocol stack which is
a diagram of foundational framework that has 4 layeres, with TCP layer operates at the Transport Layer in the TCP/ip stack.

Here is an Example Communication someone would send through the Diagram:

![image](https://github.com/user-attachments/assets/9505a1d7-2521-4b30-b7b0-6c32599336af)


We see in the Above Screenshot we have the letters A and B. A wants to send "Hello" to B, in order to do that 
Hello will get sent through the TCP/iP stack and back up through the TCP/iP stack. The string "Hello" will go through
the network layer, data link layer, and physical layer then it will go back up throght the TCP/ip stack and send "Hello"
to B.



What is UDP? UDP(User Datagram Protocol) scan is a network scanning technique uded to identify open ports on a target system. Unlike TCP, UDP is connectionless, meaning it dose not establish a handshake before transmitting data.


Here is what TCP and UDP look like drawn out in a picture.

![image](https://github.com/user-attachments/assets/2dc3e1ca-42ad-453a-a06d-840f346bedd0)


| **TCP Scan**     |   **Right Side** |
|------------------|------------------|
| Handshake required             |   No Handshake required         |
| Ensures data delivery and retransmits lost packets  |  No guarantee delivery or retrainsmit lost packet


How to do a TCP scan:


How to do a UDP scan:












