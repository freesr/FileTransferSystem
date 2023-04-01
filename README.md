# FileTransferSystem
This application, which is built on Java sockets, enables two clients to share files. It employs a peer-to-peer strategy.


The Peer-to-Peer File Sharing System consists of two files: ClientServer.java and PortListenerSend.java.

ClientServer.java contains the main method and the logic for registering files, searching for files on the Central Index Server, and downloading files from a peer server. The class also reads the IP address of the Central Index Server from a file called "indxip.txt".

PortListenerSend.java contains the logic for handling incoming download requests from other peer servers. It listens on a specified port for incoming requests and sends the requested file to the peer server.

To use the Peer-to-Peer File Sharing System, compile both files and run the ClientServer class. Follow the prompts to register files, search for files, and download files from other peer servers.
