# Ops 301 Reading02
## Network scanning with NMAP
**This topic matters because threat actors uses port to get into the system. We must know the foundations of networking in case there was ever a breach in the network if we were working for a company**

**1. What is a port? Describe it with an analogy that would help a family member understand.**
- Imagine living on an island and you are the cheif of that island. There are food that needs to be shipped into a sertain part of the island. There are many ships that come in go. The island is too big to be traveling all around just for one spot so you have docks. Think of a Dock as a port That carry spicefic type of food. If the northern part of the island get rice and the southern parts get canned goods then a ship carrying can goods must go to the southern part of the island and the rice/grains must go to the northern part of the island. 

**2. What does a port scanner send to a port to check the current status?**
- A port scanner send a network request to a specific TCP and UDP port to see if there is anyway that it can come in if there is too much traffic

**3. When a port scanner sends a request to connect, what are the three possible responses? Describe them.**
- Open, Accepted - Ask for permission and what it can do.
- Closed, Not Listening - The computer states that it is not availble due to traffic.
- Filtered, Dropped, Blocked - The Computer dont do shit. Doesnt even try to resopnd

**4. What is the difference between TCP and UDP?**
- TCP - TCP is like the inventory guy, When packets are send he checks if they are good to process thru. If not then he send em back to the server till they give him a good packet.
- UDP - UDP on the other hand send back bad ones. Matter of fact it doesnt even send the bad error codes back. Games and Live streaming use alot of UDP



## Common Ports

- Telnet - Login to devices remotly and can view all info in terminal. Very risky (Port 22)
- SSH - Remote terminal access to computer (port23)
- DNS - Domain name system. Coverts IPv4 of website. (port53)
- SMTP - Simple male trasnfer, Sending email to comuicate with other computers (port25/587)
- HTTP - Hyper Text Transer Protocol. Used to load web pages. (port80)
- HTTPS - Used to secure communication traffic if two mac are communicating. (port443)
- RDP - Remote Desktop protocol. Used to fully remote to another device not just the terminal. (port 3389)
- Ping - It is mostly used to test other reachable computers (ICMP)

## Things i wish i knew more of
I wish i knew more ports

Resources: 
- https://youtu.be/fgC8hk4IfDk?feature=shared
- https://chat.openai.com/share/30f5eb92-33d2-4da4-8348-92971b6761a2