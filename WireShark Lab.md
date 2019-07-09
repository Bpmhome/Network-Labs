## WireShark
### What to hand in
```
The goal of this first lab was primarily to introduce you to Wireshark. The following questions will 
demonstrate that you’ve been able to get Wireshark up and running, and have explored some of its 
capabilities. Answer the following questions, based on your Wireshark experimentation:


1.List 3 different protocolsthat appear in the protocol column in the unfiltered packet-listing 
window in step 7 above.


2.How long did it take from when the HTTP GET message was sent until the HTTP OK reply was 
received? (By default, the value of the Time column in the packet-listing window is the 
amount of time, in seconds, since Wireshark tracing began.  To display the Time field in 
time-of-day format, select the Wireshark Viewpull down menu, then select Time Display Format,
then select Time-of-day.)


3.What is the Internet address of the gaia.cs.umass.edu (also known as www-net.cs.umass.edu)?
What is the Internet address of your computer?


4.Print the two HTTP messages (GET and OK) referred to in question 2 above. 
To do so, select Printfrom the Wireshark Filecommand menu, and select 
the“Selected Packet Only”and “Print as displayed”radial buttons, and then click OK.
```
1.Start up your favorite web browser, which will display your selected homepage.

2.Start up the Wireshark software.  You will initially see a window similar to that shown in the figure below.
Wireshark has not yet begun capturing packets.

![Untitled](https://user-images.githubusercontent.com/47218652/60916589-695a7800-a254-11e9-8517-edd0717905a1.png)

3.To begin packet capture, select the Capture pull down menu and select Interfaces.This will cause the “Wireshark: Capture Interfaces” window to be displayed, as shown in the figure below.

![Untitled](https://user-images.githubusercontent.com/47218652/60916676-a4f54200-a254-11e9-818c-0faba009c82b.png)
