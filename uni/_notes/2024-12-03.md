**AOS**
Karnaugh map. Max inputs is 4, further makes the map 3D
1. Sum of product SoP - remove brackets
2. Truth table - find conditions for gate output to be 1. Group the 1s through box TT. Make biggest groupings available with no diagonals and the lowest number of groups. You can group at table edges.
   Use the pattern 00, 01, 11, 10 in table
4. Group the 0s
5. Reading the groups. Groups are in base 2. So group of 1, 2, 4, 8
     Start with rows and columns. If a value in the group is 1 and 0 it is irrelevant. Label the group the relevant value

**Programming - collection types**
**List** 
List values are mutable, this makes lists dynamic. Selecting an index of the list you can set the value found at that index. `list[-1] = "hello"`
Operators +, * are same as strings
indexed values can be indexed 
methods include:
     append() - add given value to the end of list
     remove() - remove first instance of a given value in the list
     index() - return index of first instance of a given value in the list
     sort()
     `del list[index]` deletes the value at given index
list of lists is called matrix, spreadsheet, 2D array in other languages.
**Dictionary**
data stored as {key:value}
Indexed by keys

**Tuple**
Useful for combining two or more bits of info
immutable, ordered
Examples - when returning multiple values from 

**Set**
In python set()
mutable
unordered
data is unique
operators:
     union |
     comparison operators <, > 

----------------
**Networks**
*Multiplexing*
*Know what questions to ask for selection*
Media selection
     What media is the infrastructure using. Cables, devices
     Future proofing required
     Considerations:
         Max data rates
         Max cable length
         Electrical interference 
         Costs of medium - planning, deployment, cable cost
         Infrastructure constraints
         Physical constraints - layout of cabling and devices. e interference from physical things. Weight of cable(potentially too much for building safety)
Modulation
     Converts digital into analogue 
     MoDem, usually included in the router
     Receives signal, converts to binary, binary read to convert to data that signal was form does this at the rate of kbps.
     Operates at highest available dial-up
     Standards:
        V.54 loopback testing
        V.250 command sets
     Uses RS-232 interface, 32 pin plug where each pin is for different process.
Connection interfaces

Data throughput

General notes:
Analogue and digital links
ITU-T, V-series are typical standard
Reasons for digital:
     Computer data is digital
     Higher data rates available
     Lower error rates
For digital telephones DSU/CSU adapters can be used.  V.35 for higher speeds.
V.35 interface
X.21 interface
T1/E1 up to T3/E3, E4
Dual ring implementation, 50ms
Extra research:
ISDN
     Intergrated digital serv
PSTN

PCM

SDH
     Synchronous Digital Hierarchy for world
SONET
     For usa
