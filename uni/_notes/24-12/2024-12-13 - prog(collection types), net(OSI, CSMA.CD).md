Construct an argument 
Point - counter point

Utilitarian 
Justice Sandel

----
String operators apply to lists
You can concatenate and multiply

Strings are immutable, lists are mutable.

List methods:
append()
     Add to the end of a list 
index()
     Return index value of the first occurrence of a given value in a list
count()
     Count how many times a given value appears in a list
remove()
     Remove the first instance of a given value in the list
sort()
     Sorts in order of numbers or words
reverse()
     Reverses the order of the list

**Sets**
Sets {} are mutable and have unique data, you can't have duplicate data in a list. An empty set is created using set() not {} as this is a dictionary.
Sets are unordered, meaning they can't be indexed

remove() and add()
Operators:
     | union
     Returns a new set that is a combination of the given sets, removes duplicates
     & intersection
     Returns a set that contains the matching values in both sets
     - difference
     Returns a set that contains the values in the first set that differ from the second set.
     <= subset and < proper subset
     Returns true if the first set, usually smaller, contains values that are in the set you are comparing it to. False if there is a discrepancy.
     >= superset and >proper superset
     Returns true if the first set, usually larger, contains the values of the set you are comparing it to

**Dictionary**
Dictionaries are unordered. They are indexed using keys. Each key has a value assigned to it. This value can be any data type including lists, sets or tuples.
When indexing, if the key doesn't exists it creates an error.
get()
     Takes two parameters, a key and a default value. Returns the data at the key index or returns the default value if the key doesn't exists
keys()
     Returns all keys in a dictionary 
values()
     Returns all values in a dictionary
 The values returned by the two methods are not in a list but they can be by using list()
To assign values we use the syntax:
     `dict[key] = 1234`
     `dict[key] += 1234
The second adds the value to the data stored at the key index.


You can unpack tuples in a for loop by assigning the values of the tuple.
     For x,y,z in tuple:

check_key()

----
CSMA/CD

1. Frame ready to transit 
2. channel clear?/ Medium idle?
3. Transmit
4. Collision? N = end
5. Broadcast error
6. Max attempts reached? Y = end
7. Allocate random backoff time(unique key). Random because it is the fairest system. 


OSI model
1. Physical (wires, voltage levels, modulation/demodulation, hubs)
2. Data link (MAC, switches, error control)
3. Network(IP, IP addresses, route)
4. Transport (TCP, UDP)
5. Session (establish, maintain, terminate)
6. Presentation (Encoding, encryption/decryption of payload)
7. Application (SMTP, HTTP)

The process starts at 7 if you are sending
It starts at 1 if recieving.

At layer 3 the process proceeds if the addressing protocol determines that the packet is meant for you. Otherwise the packet is forwarded or discarded.