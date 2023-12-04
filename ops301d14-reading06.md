# Ops Reading06
## NAT (Network Address Translation)

**1. What is the main purpose for implementing NAT on a network?**
- Main purpose for NAT is to assign a private IPv4 into a public one. It also translate to port numbers as well.

**2 At what layer of the OSI model does NAT happen?**
- NAT happens to fall in the 3rd layer of the OSI model(Network Layer). 

**3. What happens to packets when NAT runs out of addresses in the pool of available IPs?**
- As a packet runs thru the router, It performs a Network Address Protocol and then switches changes the IP to a brand new one where it can be read over the global network.

**3. What disadvantage does using NAT pose for routers?**
- The translation results in switching path delays.
- Certain application will not work correctly when NAT is running
- Routers tend to tamper with port numbers and that is a no no. 

## I wish i knew more about 
NAT vs Bridged

### Resources 
https://youtu.be/JAYpfBvGVI8?feature=shared

https://www.geeksforgeeks.org/network-address-translation-nat/