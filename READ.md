# Vehicular Coordination Using P2P Network

#### By Vanshika Sinha

## Structure

This model consists of two systems, i.e., Client-Server and Peer-to-Peer. The Client-Server connection is present when a new client is getting added to the network and is helpful in the future for broadcasting SOS alerts to only the SOS responders. The Peer-to-Peer connection is present between every client and is always active by listening to any messages sent by any one of them.

## Network Model

* V2V communication uses DSRC and TCP protocols.
* V2P communication uses DSRC and TCP protocols.
* N2S communication uses TCP/IP protocols.

## Code Instructions

* Extract the files from the .zip file provided.
* Open one instance of the terminal in the same folder containing the files and run "python server.py".
* Run another instance of the terminal in the same folder and run "python client.py".
* The message "Vehicle has started connection to the server" ensures that the code has successfully created an instance of a client.
* Try some keywords like "ACCIDENT", "MALFUNCTION", "TRAFFIC_AHEAD" and "DIVERSION_AHEAD" to check if the code is behaving as it should.

## Unique Selling Points

The proposed model can be upscaled further to various other sectors like V2I, V2P and V2N other than V2V communication making it unique from others. The vehicles can even communicate on their own without the need of a centralized server in a peer-to-peer fashion.