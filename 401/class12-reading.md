### What is the benefit of transforming data into packets? 
You don't occupy a dedicated line, you can resend lost packets.
### UDP is often refereed to as a connectionless protocol. Why is this?
Signals are sent before waiting for a handshake
### Can a socket server application have multiple socket connections?'
Yes
### Can a socket connection application be connected to multiple socket servers?
Yes
### Can an application be both a socket server and a socket connection?
Yes

### Observer Pattern
A pattern in which a server monitonrs all the clients that are subscribed to it and sends them updates
### Listener
A part of code that waits for an event to happen
### Event Handler
Code that fires on a specific event
### Event Driven Programming
Using event listeners to drive the functionality of your program
### Event Loop
The functionality behind the javascript engine. While there is an event to process, proccess the next available event.
### Event Queue
The list of items waiting to be fired by the JS engine
### Call Stack
A stack that functions get put on when called in code. FILO
### Emit/Raise/Trigger
Send out an event to some listeners
### Subscribe
Listen for a particular event
### database
store your data in an organized and longterm way

### Which 3 things had you heard about previously and now have better clarity on?
  - socket.io
  - namespaces
  - rooms
### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - client vs server socket
  - rooms but correctly
### What are you most excited about trying to implement or see how it works?
  - combo http/socket servers
