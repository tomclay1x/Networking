# Networking

Understanding Networking Protocols
What are protocols?

Protocols is set of rules.
These rules are defined by some terms 

-	Physical connection 
-	Hand-shaking (initial exchange)
-	Negotiation of parameters (series of action to establish the rules)
-	Messages delimiters (starting and ending point of a message)
-	Message format (structure “field” level)
-	Error detection
-	Error correction 
-	Termination of communications

While we use internet download something they chop it into packets. These packets contain some information about starting and ending point.


# Networking Devices 

Switch 
Layer two level devices that info about your mac address.
Switching data(packets)
Devices communicating through switch belong to same network (IP).
Switch maintain MAC address table. == mapping of switch port table.
   By numbering them of their port number.
   
  Switch perform three actions:
•	Learn
•	Flood 
•	Forward

*Learn = update MAC address table with mapping of switch port with source MAC address.
*Flood = duplicate and send the packets to all switch ports.
(Contain packet have info SRC [sources] and DST [destination])
*Forward = DST host reply to SRC by sending packets    

