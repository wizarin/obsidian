Survey
  Broad view of the topics being discussed within a theme.
Google scholar
Ebsco 
OpenAI **blog**
ChatGPT
Perplexity

Specify the level of previous understanding when questioning AI. E.g. age, first year undergrad student.

---
## **Networks Practical**
Switches use a forwarding table which is initially empty.
When a switch receives a packet, it records the Mac address of the source device and the port that it came in through. It records this data in the table, assigning the mac address to the port.

If the destination address is not in the table the switch will broadcast the packet across all ports excluding the port that sent the packet. The packet will be received by the destination address in the packet header and then a protocol edits the packet header to swap the source and destination address around to then send the packet to the switch.

The switch receives the packet and assigns in the forwarding table; The source Mac address of the packet it just received(after the broadcast) to the port on the switch that it came from.

The switch then forwards the packet to the destination heading in the packet header, which is what the source address initially was. Because the address is already in the forwarding table, the switch unicasts to the destination address in the packet header.
This completes a packet being sent forward and back between two devices.

## **Cables**
10baseT
(twisted, copper) or baseF(for fibre)
base is to do with the physics of the cable
10 is the max cable speed in MB/s
1000 would be the same as 1 GB/s
In theory max length for copper cables is 100m. This is based on the maximum amount of energy that the cable can hold. In practice it's lower due to energy loss (through heat).

Crossover cable - a pair of wires is swapped at one end of the cable
straight cable, copper - both ends are identical

Fibre cables have two cores
     Silicone
     Glass - expensive, fragile