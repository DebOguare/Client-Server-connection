#  TCP/IP Echo Server and Client. #

## This project demonstrates a basic implementation of the TCP/IP stack in python. 

The project implements a TCP/IP-based communication system, featuring a server that establishes a socket to listen for incoming client connections on a specified IP address and port. Upon successful connection, the server processes incoming data packets from the client, echoes the received payload back to the sender, and maintains the connection until the client terminates communication. Concurrently, a client module is designed to initiate a TCP handshake with the server, transmit a predefined message in binary format, and receive the server's response, which is then decoded and displayed to the user.


## How to set up a simple server-client communication 
1. Install Python 3.9+
2. Clone Repository on local machine using Git
3. Create a virtual environment for the project folder
4. Write the server code then write the client code
5. Open the terminal and navigate to the project directory
6. Run the server then the client

## Limitations
1. This server handles one client at a time in this implementation.
2. Both server and client run on the same machine. ('127.0.0.1)

## Resources
1. https://youtu.be/vKFLgmSC6do?si=4jmCJMxS70hHLp5L
2. https://youtu.be/sUzM-vIC-s4?si=M5a2dEhK6EKyMlgZ
3. https://www.researchgate.net/publication/371036975_Python_TCPIP_libraries_A_Review
4. https://realpython.com/python-sockets/
