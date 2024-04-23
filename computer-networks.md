# Computer Networks

### Adventages

### Disadvantages
- Expensive
- Complex to manage

### Network Node
- A physical device that's part of a network

### Modem
- MOdualtor DEModulator
- Enables a computer to transmit data over telephone lines
- converts digital data from computers to analogue 

### Repeater
- Each type of cable (copper, fibre-optic. etc) has a maximum usable length
- It weakens if it goes over, thats what the repeater fixes

### HUB
- hardware device used to connect computers via ethernet cables to share packets, has a repeater
- every packet is duplicated and sent to every computer. its a security risk and bandwidth killer
- cheap easy but can only sent one packet at a time

### Network Bridge
- joins HUB's together

### Switch
- replaced hubs and bridges
- connects devices together and stores the addresses of all devices that are connected to it
- the swtich only sends the incoming packets to the designated recipient
- only transimt data within a network
- requires a router
- allows Virtual Networks to be made

### Router
- transfers data from one network to another in an inteligent way.
- When a packet arrives, it reads the destination and sends it along

### Gateway
- connects networks that have different protocols

## Types of networks
### Personal Are Network
- created by a person or individuals. cimputer phone etc

### LAN
- limited area, e.g. school
- uses cables or bluetooth, and stuff

### Wide Area Network
- collection of LAN's spread over large area, including countries
- e.g. ATMs

## Network Topology
### Physical Topology
- Map of cables and PC's and how they connect

### Local Topology
- Shows data transfer and network communicatiosn

### Bus Topology
- all connected to a backbone cable, sends a message to all devices with a destination address, like the HUB

### Star Topology 
- Central node, often switch is used to direct data through the network, uses MAC addresses

### Mesh Topology
- All devices are connected
- found with wifi
- not a hub or switch, they are all connected

### Ring Topology
- all devices conected to 2 devices
- data travels through each neighbour(one-way system) until it reaches the intended recipient
- every device acts as a repeater

# Network Protocols
- A protocol is a set of rules on how to transfer data, rules of communication
- an example of astraction and decomposition
- expampels include TCP/IP and OSI

## IP
- Each device on a network is given a unique adress, used when transfering data

## MAC
- Unique serial number assigned to each network interface controller
- its a list of hexadecimal numbers
- **you can change IP but not MAC**

## TPC/IP Model
- Transmission Control Protocol/ Internet Protocol

- Application Layer
    - Where apps operate, handles communcations between apps and services, e.g. email, VoIP
- Transport Layer
    - data delivery
- Network layer
    - addresses and packages the data and route via IP protocol
- Link/Physical Layer
    - .

# Application Layer
## HTTP
- Protocol used to communicate with  

## HTTPS
- SSL: Secure Socket Layer
- TLS: Transport Layer Security

## FTP
- File Transfer Protocol
- for file transfer and not viewing websites

## SNMP
- Simple Network Management Protocol
- Monitors the network basically

## POP3
- Post Office Protocol
- Allows users to retrieve and organise mails from the mailbox on their mail server to their computer stored locally 
- It deletes messages once they are recieved

## IMAP
- Internet Message Access Protocol
- Allows users to access their mail from anywhere
- IMAP doesnt download or store mail, e.g. gmail

## SMTP
- Simple Mail Transfer Protocol
- Used for sending mail

## VoIP
- Voice over IP
- allows voice calls over the internet

## DNS
- Domain Name Server
- converts domain names to IP addresses
- Uses UDP in transport layer

# Transport Layer
## TCP
- Transmission Control Protocol
- requires established connection before transmission
- When it sends a packet, it will wait for confirmation from the recipient, stable connection

## UDP
- User Datagram Protocol
- No error correction, quick, used for voip or videos
- sends packets, guarrantee reception

## Network Layer - uses IP
- forwards packets to the correct place
- IPv4, 32 bits
- IPv6. 128 bits, 8 sets of hexadecimals
- IPv6 better because faster, securer, end-to-end encryption

## ARP
- used to discover MAC addresses

## Physical Layer
- the wires and stuff

## Wi-Fi
- Wireless Fidelity, uses radio-waves, wireless internet

## Ethernet
- the wifi cable, more secure, not interceptable

## OSI
- Open Systems Interconnection
- Divides comunications into 7 layers

## Client server model
- Client wants info, server has and "serves" it
- HTTP request and response
- This is an example of **Distributed Computing**, where the workload is shared over more than 1 machine
    - Makes it more secure to attacks(spam requests)

## Cloud Computing
- Storing files online, e.g. google drive, netflix, google docs, office
- Data is stored in **Data Servers**, fast, therefore energy consumption is high and expensive
    - **Advantages**
    - Users only need to pay for what they need
    - It's easily expandable, flexible
    - Access to up to date software
    - Easily share files
    - **Disadvantages**
    - dont know where the data actually is
    - security risk
    - need internet to access

## SaaS - Storage as a Service
- amazon web service
    - **Advantages**
    - reduced cost, availale on any device
    - **Disadvantages**
    - yeah idk

## IaaS - Infrastructure as a Service

## SaaS - Software as a Service
