**AOS**
Eventually all code is made into circuits using gates. 
Circuit efficiency - reduce amount of gates.

Jan exam - Boolean algebra,

**Laws and roots**
(ors are +, ands are * ,  )
Common factors for simplification
Steps for simplification
     Demorgans
     Distributive 
     Apply rules and laws
     Dist
     Repeat until simplified

LAWS
1. Commutative inputs AB = BA 
2. associative A(BC) = (AB)C
     And logic
3. Distributive A(B+C) = AB + AC
4. De Morgan's (AB)' = A' + B'
    (A+B)' = 
    Swaps or gate to and gate and vice versa. Based on not outside of bracket. Start simplification here

RuleS(rules)
1. A + 0 = 0
2. A + 1 = 1
3. A * 0 = 0
4. A * 1 = A, any input can be written as A1
5. A + A = A, remove duplicate terms in when adding
6. A * A = A, remove duplicate
7. A + A' = 1
8. A * A' = 0, any AND term containing this is zero too
9. (A')' = A, the two NOTs cancel
10. A + AB = A1 + AB = A(1 + B) = A1 = A
     A + AB = A
11. A + A'B = A + AB + A'B = A + B(A + A') = A + B(1) = A + B
     A + A'B = A + B
     Using r10 to make common terms
12. (A + B)(A + C) = AA + AC + BA + BC = A + AC + BA + BC = A + BA + BC = A + BC

---
**Programming**
Return ends the function, even in a loop
Return (expression) can return the result of the expression. Any using == returns bool.

Range(start,stop,step)

Outer loop
     Inner loop

**Decision structures** 
 **If statement** 
 checks an expression to execute statements. If, else good for binary choices.
 Elif and else at the end to guarantee one branch of if being executed. 
 if char.isdigit(): this is a function that returns a bool so if (bool):

If temp >= 20 && temp < 23:
     return None
If temp < 20:
ElIf 20 <= temp < 23: can remove 20 <= as condition is checked by previous branch of if >

**Boolean expressions**
Comparison operators
Logical operators
     Not and in
Short circuit
     If x and y: 
     if x condition is not met then y is not checked

---
**Networks**
IP addressing is Indirectly related to security and system management.

IP is
     Connectionless, no data revovery
     Uses IP addressing system
     Static(set by user, constant) and dynamic(found using dhcp)
IP has two sets of tasks, recieving data and transmitting data

3 key address fields
     Unique 32 bit address 
     Subnet mask, looks at what can and can't be sent
     Default gateway - optional identifies the address of the router

IP Addressing is divided into 2 areas, it start by looking at Network ID and then Host ID(pc).
Sending is done using ARP. 
On layer 3 (Network Access Layer)
ARP broadcasts to check if address is on the current network
ARP will translate IP into MAC address.

On layer it checks the datagram for corruption before handing it over to the next protocol. 
IP HEADER CONTAINS - 
Ivpv4 32 bits, ipv6 128 bits 
at least 20 bytes
     Send and receive address, hop count
     Header is read and added to/edited by other protocols

Version, Internet Header Length, Type of service, total length, flags, fragment offset, protocol, header checksum, source IP, IP data payload

Type of service is what the data is for, video, email, livestream. Low or normal, normal or high throughput(video), 
Identification, Unique ID
Total length, packet length in octets
Flags, DF, MF 0 to say to no more fragments left
Fragments offset, sets a value for each fragment so data can be remade
Time to live, seconds or hops the datagram can survive
Protocol, the one being used 
Header checksum, 16 bit value to confirm header

Public and private IP addressing
A unique IP is public, every computer has one.
Router has a unique public IP, the connect between internal and external network.
Pcs on a LAN share network ID.
Each pc has a unique host ID.
The two IDs combine to make an IP address
All IPs on a network require unique IDs (global network vs local )

Servers can have multiple addresses by using multiple NIC cards.

CLASS examples on slides.
A B C 
D for multicasting
E for experimenting, research for potential future applications

