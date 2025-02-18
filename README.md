Securing communication with TLS/DTLS on ESP32  

In this project, we send an HTTP GET request to an online REST API HTTPS server and read the response from it.  

When the client application tries to connect to a server, a process called a TLS handshake happens initially.  

The server is authenticated on the client side by checking its certificate to see whether the certificate is issued by a Certificate Authority (CA). This step is important since the client needs to know whether the server is legitimate. Ther certificate is in 'server' directory.  

When the TLS handshake is successful, the parties can communicate over any secure application layer protocols, such as HTTPS  


