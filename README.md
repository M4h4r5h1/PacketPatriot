# Packet-pratriot
## A packet tracer which analyses IP address connection and blocks message.

Packet patriot is a simple attempt to showcase how a packet tracer works. Here I have used a Java code to create a GUI that displays a message pasing model over a network. Our attempt was to disallow any blocked content over a network as any such validation is hardly available in the market. Hope you like and understand the project as instructions follow.

## Prerequesites - Install any Java based IDE like Intellij or Netbeans.

## Instructions

1. Frstly, download all the files from firewall folder (would take only 4 minutes or less).
2. Move these files to one single folder if you have not added already.
3. Then open that in your IDE and setup the SDK(Software Development Kit), and you are ready to run the program.
4. Go to the firewall.java file and run it.
5. Two windows will open (Client and server side).
   - You have to first establish a connection with the server.
   - The IP has to be of the same class (like 127.0.0.2 or 127.0.0.5), port opened for use is 80 (you have to enter these details).
   - After connection is established on client side you can set server rules (server tab) from the server side.
     - Here you can add/delete blocked strings and IP addresses.
   - Now type the message to be passed and send packet(it will be blocked if it contains any blocked content).
   - 'Log' tab is used to see the various messages that have been passed earlier.
6. Following the above steps you can run the code successfully!

You can contribute to the code by puuling or forking as well as inform me about any bugs or issues with the files.

## Known Issues
The project is not yet scalable but can be used for demonstration purpose. My aim is to make it accessible for commercial use. 
