# Ops 301 Reading01
## Network Traffic Analysis with wireshark
### OSI model is very important because it the guide to network traffic

**1. What does "OSI" stand for?**
- OSI model stands for Open Systems Interconnection Refernce Model

**2. List the 7 layers of the OSI model and what each one is responsible for.**
- Physical - Actual physical connection between devices. Transmitting bits from one node to the next
- Data link - Foundation layer for the other layers. DLC protocol, Mac address. Switching layers because of switches 
- Network - Also known as the "routing" layer because it connects with IPv4. Frames are fragments to traberse different networks
- Transport - Transport data and tells it where to go and how its going to be transported.  TCP protocol, UDP protocol. Split of frames across the network and they build together on the other side where the clients sees the full website. 
- Session - It is design to start and stop from one end point to another. Control protocols and tunneling protocols. Communication Management
- Presentation - Encoding. Takes all data and forms it so user can understand and see. 
- Application - The final product. What user sees.

**3. Distinguish which layers are the "Hardware layers and which are the "software layers" What does that even mean?**
- I would say that the hardware layers is layer 1 the physical layer. where it has Cables ,fiber,etc. And the software layer is Layer 4 and on because starting the frames and sending them to the user bit by bit and finally the reaching the application where the user can see the software.

**4. How can the OSI model be used for trouble shooting?**
- The OSI model can be used for trouble shooting when there is a probablem with the network or connection. We can always look back and see how the network is used with the OSI model. I look at it like a map. 

## What is wireshark and how is it used?

**1. What is WiresharK**
- Wirkeshark is a network portocol analyzer or a app that captures packets from the network. Wireshark is used to "sniff packets".

**2. What is a packet?**
- From what i believe i believe a packet is a packet of data. I could be wrong but pack is data used from the network and travels to the end user.

**3. What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?**
- Packet Capture - Can be used to capture sensative data. Admins uses this tool to analyze threats or traffic and see how well everything is.
- Filtering - Admins or whoever is using Wireshark can use filter to see vulnerbilities or weaknesses. Helps to see how different divices work and to see if the app is following standards
- Visualization- It allows the user to go straght to the middle of the packet and see what all is happening. Can be used to troubleshoot network very well

### Source:
 https://www.professormesser.com/network-plus/n10-008/n10-008-video/understanding-the-osi-model-3/

https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it

## Things i wish i knew more about.
I wish i knew more about how wireshark works. I can read the artical but i want to be able to use it first hand