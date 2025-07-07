# day8
training

# Networking commands:

## ping:

it means : "Hey, are you there?" It's used to check if another computer, server, or website is currently online and reachable from your PC. ping sends ICMP (Internet Control Message Protocol) Echo Request packets to a target host.

If a reply is received, the host is active. Otherwise, its blocked. Syntax: ping website_address

## loopback Address (127.0.0.1):

This IP always refers to "yourself" – your own computer.It's used to test the network configuration of your local PC. Example: Like sending a letter to your own house to test if your mailbox works.

## TRACEROUTE:

The traceroute command is a network diagnostic tool used to track the path that data packets take from your computer to a specified destination, such as a website or an IP address. It helps identify network problems by showing each hop (router) the packets pass through and the time it takes to reach each hop.

### How Traceroute Works

Traceroute sends a sequence of packets using the ICMP protocol, similar to the ping command. Each packet has a time-to-live (TTL) value that starts at 1 and increments with each subsequent packet. When a packet's TTL reaches 0, the router discards the packet and sends an error message back. This process continues until the packet reaches its destination, allowing traceroute to map out the path and measure the delay at each hop.

#### Using Traceroute

To use traceroute, open a command prompt or terminal window. On Windows, type cmd in the search bar and press Enter. Then, use the following syntax:

tracert [hostname or IP address]

## IPCONFIG:

The ipconfig command is a powerful tool in Windows that displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings. It is commonly used for troubleshooting network issues and managing network settings.

### Basic Usage

This will display the basic network information for all network adapters, including IPv4 and IPv6 addresses, subnet mask, and default gateway.

#### Syntax:

ipconfig websitename\ipaddress

|Term|	Represents|
|-----|-----------|
|inet	|IP address|
|netmask|	Network range|
|lo0	|Loopback|
|broadcast|	Address used to send messages to all devices|

## Comparison of Network Types

|Network Type|	Definition	|Type|
|-------------|-------------|-----|
|Ethernet|	A specific wired technology for local area networking.|	LAN Technology (Wired)|
|Wi-Fi	|A specific wireless technology for local area networking.	|LAN Technology (Wireless)|
|LAN|	A network connecting devices within a limited area (e.g., home, office)|	 Local Network|
|WAN|	A network that spans a large geographical area, often connecting multiple LANs	|Wide Network|
|Internet|	A global system of interconnected networks using the Internet Protocol (IP) suite.|	Global WAN|

## Ethernet

#### Definition:

Ethernet is a wired networking technology used to connect devices using a physical cable, allowing them to communicate or access the internet.

### How It Works:

^ Plug one end of an Ethernet cable into your PC's Ethernet port.
^ Plug the other end into a modem or router.
^ Your PC can now connect to the network or internet.

## Ethernet vs. Wi-Fi

Ethernet
Definition:

|Feature|	Ethernet|	Wi-Fi|
|Signal	Through cable |(copper/fiber)	Through air (radio waves)|
|Speed	Faster	Varies |can be slower than wired|
|Stability|	More stable|	Can be affected by walls, distance|
|Security	|More secure	|Less secure
|Mobility|	No (wired)	Ye|s (wireless mobility)
