# Reading Notes 13

## Message Queues

### What does it mean that web sockets are bidirectional? Why is this useful?

it is when data can be sent in either direction with one socket, which is obviouly more useful than only being able to send 1 direction

### Does socket.io use HTTP? Why?

no, because https is not biodirectional. hover if the websocket is not working, it can use http

### What happens when a client emits an event?

if the server is listening for the event, it will broadcast the event out to every client within the network.

### What happens when a server emits an event?

whoever the server decides will hear the event will hear it and react to it

### What happens if a client “misses” an event?

Then it is just missed. It cant be saved if the client is not listening

### How can we mitigate this?

we can use volatile events.

## Terms

Socket: One endpoint of a two way communication link between two programs running on a network.

Web Socket: a computer communications protocol that provides full-duplex communication channels over a single TCP connection.

Socket.io: a node.js framerwork for implementing websockets

Client: one of the endpoints in a network that is not the "central node"

TCP: a connection oriented communication protocol for clients on a network.

Packets: pieces of data that are bundled together to be passed along.
