## **Star**
![[star.png]]
Pros:
	Network still functions if one node fails
	Depending on central node, can accommodate heavy traffic
	Easy to add or remove nodes
	More common today
Cons:
	Single point of failure in central node
	The effectiveness of the central node determines the efficiency of the whole network

## **Bus**
![[bus.png]]
*Legacy*
Pros:
	Relatively good rate of data transmission
	Simple to implement
	Easy to add nodes
	Potentially requires less cable than star, so cheaper
Cons:
	Uses coaxial cable so can't cope with heavy traffic
	Performance degrades as nodes increase
	Prone to collisions
	No redundancy, cable breaking can disable entire network, hard to troubleshoot
	Number of nodes limited by cable length
	No longer popular due to limited range

## **Token Ring**
![[token ring.png]]
*Legacy*
Pros:
	All nodes get an equal chance to transmit data
	Good quality of service (QoS)
	No collisions
Cons:
	One node or cable breaks and whole network could shut down
	Tokens could be lost or corrupted
	Difficult to add/remove nodes
	No longer popular due to limited range

## **Mesh**
![[mesh.png]]
Pros:
	Redundant paths between devices
	Easy to expand without disrupting users
	Easy to reroute traffic if cable/node fails
Cons:
	Requires more cables than other topologies, so more expensive
	Complicated to implement
	Large amounts of redundancy

## **Partial Mesh**
![[partial mesh.png]]
Pros:
	Reduced complexity by having less connections
	All nodes have a connection to more than one node but not ALL nodes