# NeudoseCDH
A Server Client TCP communication written by C

How to start: (SQLite must be installed)

1. Clone the repository to your Mac/Linux.

2. Cd into NeudoseCDH folder.

3. Using command:   $make     to perform makefile compiling (make sure gcc is installed).

4. Open up two terminals on your Mac/Linux (also works with two different computers, just make sure the IP address is reachable).

5. On the first terminal, start server by typing command:     $./server #YOUR IP ADDRESS# #PORT# 
(ex:  ./server 192.168.0.126 10000).

6. On the second terminal, start client by typing command:    $./client #YOUR IP ADDRESS# #PORT# 
(ex:  ./client 192.168.0.126 10000).

6. Now the communication is built, do a User Login in (username: neudose1  password: 123).

7. Query the status you want on the client side (ex: batterylevel, humidity, illumination, temperature & solarpanel).
