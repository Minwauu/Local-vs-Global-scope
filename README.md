# Network topologies

### The different ways computer connections and devices are arranged are called *topologies*.

## Bus topology

- The bus topology is where there is *one* cable that connects every device on the network, aka the *backbone*. At each end of it are devices called *terminators* which absorb the signals when they reach the end to prevent interference. 

![image](https://github.com/Minwauu/Network-topologies/assets/110039102/77e1fefb-5d75-4993-900c-ac16ea51f81c)

- If two or more devices try to transmit at the same time in a bus topology, it will cause a *collision* e.g a signal interference. If a collision occurs, the devices must stop and try again later at random waiting times each. When the network is being used heavily --> lots of devices transmitting data --> lots of collisions. Performance of the network deteriorates.

- The fact that signals are transitted across the whole network can be a security issue because every device attached to the bus can "read" every message, unless the messages are encrypted.

- A failure of the main bus cable will bring the whole network to a stop. However, if there is a break or failure in the cable that connects a single device to the bus, it will affect just this device; the rest of the network will carry on working.

- You will rarely encounter a physical bus network in real life. It is tricky to lay a heavy cable through the centre of an office and to have multiple connection points leading into it. Today's local area networks are based on bus technologies, but are more likely to be cabled as a star using a hub or a switch as a central point of connection. Such a network can be described as a logical bus network.

![image](https://github.com/Minwauu/Network-topologies/assets/110039102/4e3a60f4-34ed-4951-b53a-c58cafedf9b6)


