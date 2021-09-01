### What does it mean that web sockets are bidirectional? Why is this useful?
Any socket can both send and recieve information
### Does socket.io use HTTP? Why?
It does not. It uses a connection protocol that is layers below http, and therefore faster
### What happens when a client emits an event?
It gets sent to the socket or namespace it is connected to
### What happens when a server emits an event?
It gets sent to all the client "listeners"
### What happens if a client “misses” an event?
It doesn't fire the handler
### How can we mitigate this?
Fire multiple events

#### Socket
An endpoint in a 2 way real time connection
#### Web Socket
A socket connected over the web TCP protocol
#### Socket.io
A javascript library for creating web sockets
#### Client
The individual side of the web socket connection
#### Server
The main hub that all sockets connect to
#### OSI Model
 ["a series of protocol layers with a specific set of functions allocated to each layer"](https://docs.microsoft.com/en-us/windows-hardware/drivers/network/windows-network-architecture-and-the-osi-model). Source: Microsoft Documentation
#### TCP Model
A faster, more concise model for internet connections that only contains 4 layers
#### TCP
A faster, more concise model for internet connections that only contains 4 layers
#### UDP
Very fast connection protocol that sends packets before a handshake
#### Packets
A small parcel of data that was bundled together and sent over the internet. The order of packets recieved is also noted.

#### Which 3 things had you heard about previously and now have better clarity on?
1. Rooms vs namespaces
2. The persistance of socket connections
3. Automated socket connections
#### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. Deploying socket.io servers
2. Combo HTTP / socket based servers
3. Securing socket connections
#### What are you most excited about trying to implement or see how it works?
Combo HTTP / socket based servers
