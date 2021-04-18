# Client-Server-Chat-Application

Chat Application (Client-Server) using C language, sockets and threads.

Compiling files :

* Serveur :
`
gcc serveur.c -pthread  -o serveur -w
`
* Client :
`
gcc client.c -pthread  -o client -w
`
Executing the code, connection established :

<p align="center">
  <img  src="images/connection_established.PNG" width="600px" >
</p>

3 Clients connected to the server:

<p align="center">
  <img  src="images/clients.PNG" width="600px" >
</p>

Listing the clients that are connected to the server with the command **LIST**:

<p align="center">
  <img  src="images/list.PNG" width="600px" >
</p>

Sending message to a client with the command **SEND X Message** (X is the id number of the client):

<p align="center">
  <img  src="images/send.PNG" width="600px" >
</p>
