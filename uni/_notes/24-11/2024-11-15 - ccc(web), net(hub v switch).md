Huggingface.com

**CCC
Git status

Git diff

Bug comes up on feature branch. Pull main, fix bug, push. Pull fix to feature branch.

---
**Networks**
Hub Vs switch
Hub broadcasts to all devices connected to it, this create extra traffic on the network.
Switch process the protocol and sends to the appropriate device on the network.
Switches have a register 'table'. This table assigns the ports in the switch to the IPs of devices connected to said ports.
A switch receives the packet, it reads the port that the packet is sent in from and assigns the IP that sent it to that port.
It uses ARP packets.
A hub has no register, it just broadcasts to all devices.

Examples register:
fa0 is 192.168.0.2
fa4 is 192.168.0.4

(fa0 is is fast ethernet port 0)
ARP associates IP and MAC address together

Impact factor refers to the impact a point of failure will have on the total network (25%).

Fault tolerance and cost, trade one for the other. 
Coursework networks will be judged on fault tolerance, cost, network bandwidth