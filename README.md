<h1> Original code of broadcast chat </h1>

![alt text](image.png)

> The client and server is connected through a websocket. The server will listen to the port that connects to a websocket then also connected to each client. When a message was sent from client, then the server will forwards it to all other clients available. Thus why, when I sent a message from one client, the other client will also get that message from the server.
