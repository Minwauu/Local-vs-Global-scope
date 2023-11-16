# Networks

### The different ways computer connections and devices are arranged are called *topologies*.

## Bus topology

- The bus topology is where there is *one* cable that connects every device on the network, aka the *backbone*. At each end of it are devices called *terminators* which absorb the signals when they reach the end to prevent interference. 

![image](https://github.com/Minwauu/Network-topologies/assets/110039102/77e1fefb-5d75-4993-900c-ac16ea51f81c)

- If two or more devices try to transmit at the same time in a bus topology, it will cause a *collision* e.g a signal interference. If a collision occurs, the devices must stop and try again later at random waiting times each. When the network is being used heavily --> lots of devices transmitting data --> lots of collisions. Performance of the network deteriorates.

- The fact that signals are transitted across the whole network can be a security issue because every device attached to the bus can "read" every message, unless the messages are encrypted.

- A failure of the main bus cable will bring the whole network to a stop. However, if there is a break or failure in the cable that connects a single device to the bus, it will affect just this device; the rest of the network will carry on working.

- You will rarely encounter a physical bus network in real life. It is tricky to lay a heavy cable through the centre of an office and to have multiple connection points leading into it. Today's local area networks are based on bus technologies, but are more likely to be cabled as a star using a hub or a switch as a central point of connection. Such a network can be described as a logical bus network.

## Star topology

- In a physical star network, each client (that is, 
a device connected to the hub) has its own 
direct connection to the central hub. The hub 
receives packets for all of the clients 
connected to it and is responsible for 
delivering them to the correct recipient. 

- A server can be added to the network in the 
same way that clients are connected to the 
central hub. 

![image](https://github.com/Minwauu/Network-topologies/assets/110039102/b932799d-f29c-4bcb-b08e-e9d2ea8c141c)


![image](https://github.com/Minwauu/Network-topologies/assets/110039102/4e3a60f4-34ed-4951-b53a-c58cafedf9b6)

## Types of Networks

There are many different types of network.

- A personal area network (PAN) is the term given to connected devices that are located within a few metres of each other.

- A local area network (LAN) is a single network that is located in a small geographical area such as someone's home, an office, or to cover a school site.

- A wide area network (WAN) is a network that connects two or more networks over a wider geographical area. Networks can be further classified as client–server or peer-to-peer. This classification explains the role that devices have within a network and is not directly related to whether the network is a PAN, LAN, or WAN.

## Wirelesss networking

- Wireless networks allow clients to communicate 
within a network without being physically 
connected to it. 

- Wireless networks require a wireless access 
point, which connects to a wired network just like 
any other client would, and a wireless network 
adapter in the device that connects to the wireless 
network. 


## Wi-FI

- WiFi is widely used to provide wireless networks 
and refers to a wireless local area network that is 
based on international standards. This allows a 
device made in one part of the world to connect seamlessly to wireless networks all over
the world.

- Wireless networks are secured by encrypting transmitted data using WPA or WPA2. WPA 
stands for WiFi protected access and requires that a new wireless client enters a
password in order to connect to the network. 
