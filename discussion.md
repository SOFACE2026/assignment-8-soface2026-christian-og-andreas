

What is an IP address? (100 words)

    Why do we need IP addresses?

    We need IP addresses to give adresses to different server and computers

    What is the relation between TCP and IP?

    IP transports the TCP packets from different servers and make sure they get to the right hosts

    What is a socket? Have you heard of different types of sockets?

    A socket is a network tool to either listen og send network data. A socket can be bound to a port if its a UDP or TCP socket however it can also be used as a RAW socket to send for example ICMP data.

    What is up with the address: 127.0.0.1?

    That is the loopback address. Any data sent to it will be received on the same host it was sent from

What does a client-server architecture mean? (150 words)

    Give an concrete example of where you would encounter this in real life.

    Webservers is a classic example where we have clients who request the webpage and receive a response from the webserver

    How do you decide who is the server and who is the client?

    It is who initiates the connection. The server is passively listening for connections but clients are actively connection to the server.

What is the difference between client-server architecture and the broker architecture? (100 words)

    What are the benefits to the broker pattern?

    A broker can decide where traffic needs to go before it gets to a server. This can be used as load balancing to balance a lot of traffic to more servers. It can also offer a layer of abstraction where the server behind the broker can be switched out without any clients knowing

    What could be potential downsides?

    More complexity in an architecture,

What does Peer-to-Peer mean? (150 words)

    What are the main characteristics of this architecture?

    Hosts connect directly to each other and not through a central server.

    Have you encountered it anywhere online?

    The torrenting file sharing protocol is based on P2P architecture, also a lot of multiplayer games use a p2p architecture

    Does Peer-to-Peer applications mean that there are no servers and only clients?

    It is more that each client is also a server for the other peers in the network

    What benefits could there be to using this pattern?

    Not dependant on a single host being up constantly. Hosts can pop in and out of the network making the network more robust.

    What downsides could there be to this pattern?

    You dont know which peers are on the network and if any of them have malicious intents

