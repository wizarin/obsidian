Open Systems Interconnection reference model
Made by the ISO, International Organisation for Standardisation

It serves as a conceptual reference model that all parts of a network can interact with. It's goal is to have open systems, meaning any operating system can be used on the network with no conflicts.

The model achieves this through seven layers, passing data up or down between them depending on where in the network it is being interacted with. At one end, the Application layer, the data is in a format that humans can interact with. At the other, the Physical layer, the data is in a format that all computers can interact with (binary).
The process starts at 1 if you are receiving a transmission and at 7 if you are sending.

1. Physical
	Transmits raw binary data across physical media using [modulation](_net_glossary)/demodulation. Handles specifications for cables, connectors and voltage levels. Devices that interact with this layer are hubs, repeaters, network adapters and physical interfaces. Protocols at this layer are Ethernet(IEEE 802.3), DSL and Wi-Fi physical components
2. Data Link
	Handles error detection and correction, MAC addressing and flow control. Error handling is done in the MAC sublayer using protocols such as CSMA/CD. Flow control refers to a process that regulates the flow of data between a sender and receiver to not overwhelm the receiver, at this layer it is limited to only devices in the local network. Devices that interact with this layer are switches and Network Interface Cards (NICs). Protocols at this layer include Ethernet, Wi-Fi(IEEE 802.11) and ARP.
3. Network
	Handles logical addressing and routing of data across multiple networks. IP addressing happens on this layer. Packet fragmentation happens on this layer, this is a process where packets are fragmented to accommodate the Maximum Transmission Unit (MTU) of the current network. Ethernet, Wi-Fi or DSL have different MTUs. Devices that interact with this layer are routers and layer 3 switches. Protocols that operate at this layer are IP(IPv4, IPv6), ARP and ICMP. When receiving data, the packet header is read by an addressing protocol and the layers only continue if the recipients MAC/IP address matches the header.
4. Transport
	Handles reliable or unreliable delivery of data between end devices. Also handles segmentation, sequencing, error recovery, flow control and [multiplexing](_net_glossary)/demultiplexing. TCP(connection oriented) and UDP(connectionless) operate at this layer. Identifies specific applications or processes and the ports they are associated with (e.g. HTTP is port 80).
5. Session
	Establishes, maintains and terminates sessions between applications or devices(the data stream between the two). Uses synchronisation and dialog control. Synchronisation is used to create checkpoints(sync points) in the data stream, this allows sessions to be terminated and resumed in the same place. Dialog control refers to the rules of communication, this can be half-duplex or full-duplex. Half means only one device can communicate at a time while full means both devices can which is the typical in modern communications.
6. Presentation
	Handles encryption/decryption of the payload(the data in the packet, not the header), encoding/decoding and compression. This layer translates the data between layer 7 and the other layers, making it readable by humans or machines.
7. Application
	Human machine interface layer, this is what the user interacts with. Handles application-specific protocols and services. Protocols at this layer include HTTP/HTTPS, SMTP, FTP and DNS.