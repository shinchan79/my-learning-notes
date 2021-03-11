# Concepts
## Principles & architecture
### A brief history of the internet
- ARPANET (1966-1967)
- Others: SAT net, Packet raio, Ethernet LAN
- 1973: replace the original network protocol with TCP/IP.
- ... 
### Problems and growing pains
- running our of address -> ipv4: only 2^32 addresses
- congestion control: -> insufficient dynamic range (wireless, high-speed intercontinental paths) 
- Routing -> no secrity, easily misconfigued, poor convergence, non-determinism
- Seurity
- Denial of service
### Internet design principles:
-> design philosohy of the DARPA Internet Protocols, Dave clark 1988 
- Conceptual lessons -> principles designed for a certain type of network
- Technical lesson -> 1) Pakcet switching; 2) fate sharing (soft state)
### Goal:
"multiplexed utilization of existing interconnected networks":
multiplexed: sharing => statistical multiplexinng/packet switching
interconnected: interconnection of existing networks => narrow waist
### Packet switching:
- in packet switching: info for forwarding traffic contained in **destination address** of packet: like send a letter. That might wend its way through multiple intermediate post offices en-route to the recipient.
- shared resouce, contrast to circuit switching - where a signalling protocol set up the entire path out - of band.
- advantange: delay
## Narrow waist
