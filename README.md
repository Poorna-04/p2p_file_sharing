# P2P-File-Sharing
Multithreaded P2P File Sharing in Java Using Socket Programming 
Created a peer-to-peer network for file downloading. It resembles some features of Bittorrent, but much simplified. There are two pieces of software – peer and file owner.
The file owner has a file, and it breaks the file into chunks of 100KB, each stored as a separate file. The file owner listens on a TCP port where the file owner is the server that can run multiple threads to serve 
multiple clients simultaneously.

## Project Requirements
Each peer should be able to connect to the file owner to download some chunks. It then should have two threads of control, one acting as a server that uploads the local chunks to another peer (referred to as 
upload neighbor), and the other acting as a client that downloads chunks from a third peer (referred to as download neighbor). So each peer has two neighbors, one of which will get chunks from this peer and 
the other will send chunks to this peer. There is a direct path from any peer to any other peer. 

## Built On
- Programming language: Java 
- Operating System: Windows 
- Programming Tool: Netbeans
