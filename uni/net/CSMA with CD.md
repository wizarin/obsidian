Carrier Sense Multiple Access with Collision Detection
Happens on the MAC sublayer of the Data Link layer in the OSI model.
Primarily used in older ethernet networks that use coaxial cables or in half-duplex environments. Used with Bus topology.

- **Carrier Sense (CS)**: Devices listen to the network to detect whether the medium is currently in use before attempting to transmit.
- **Multiple Access (MA)**: Multiple devices share access to the same communication medium.
- **Collision Detection (CD)**: If two devices transmit simultaneously and a collision occurs, the devices detect it, stop transmitting, and retry after a random backoff period.

1. Frame ready to transit 
2. channel clear?/ Medium idle? 
3. if Y - Transmit
4. Collision? N = end
5. if Y - Broadcast error to all devices on network
6. Max attempts reached? Y = end
7. Allocate random backoff time(unique key). Random because it is the fairest system. 

![[CSMAwithCD.png]]

