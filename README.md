# Client to Server Ping
## Tristan Schieler

### Description

For UDP the packet gets sent from client to Server and the roundtrip time is measured.

For TCP client makes a connection to Server and sends a message

### Compile and Run

#### UDP

* `javac PingServer.java`
* `java PingServer 'Port'`

In Seperate Terminal

* `javac PingClient.java`
* `Java PingClient 'IP' 'Port'`

#### TCP

* `javac TCPEchoServer.java`
* `java TCPEchoServer 'Port'`

In Seperate Terminal

* `javac TCPEchoClient.java`
* `Java TCPEchoClienet 'IP' 'message' 'Port'`

### Versioning
The version of this program is purely for testing and education purposes. The maker reserves the right to make updates and bugfixes.
