
## Examine

Find these features, as shown below:

Packet List in the top pane, showing one line per packet. Notice the TCP handshake performed by packets 1, 3, and 4, outlined in red in the image below.

Packet Details in the middle pane, showing the first four TCP layers. Notice MAC addresses at layer 2, IP addresses at layer 3, and TCP port numbers at layer 4, outlined in green in the image below.

Packet Bytes in the bottom pane, showing raw data in hexadecimal and ASCII form, outlined in red in the blue below. 

![123p6wire1](https://user-images.githubusercontent.com/47218652/60917438-960f8f00-a256-11e9-9daf-48a044836c2f.png)

## Finding an FTP Password

FTP is a very unsafe protocol, because it sends passwords over the network without encryption. To demonstrate that, we'll steal a password.

In Wireshark, at the top, in the "Apply a display filter" box, type ftp and press the Enter key.

Wireshark filters the packets, showing only the packets using File Transfer Protocol. On the right side, you can see the login process for a user named "john". Find John's password, which is covered by a gray box in the image below. 

![123p6wire2](https://user-images.githubusercontent.com/47218652/60917439-960f8f00-a256-11e9-97b1-c4975bb0f9de.png)
