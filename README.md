# CCNA-Troubleshooting-Work

\>EN  
\#Show version  
--> check time down or you can check the time stamps in the app  

\#SHOW INT  
\#SHOW INT F0/1  
\#show ip int brief  
ping  
ping ip  
traceroute  
\#show controller  

=====================  
**Link State** ==> up/down  
- Layer 2 and Layer 3 addresses  
- Bandwidth rate, reliability, Tx and Rx loads  
- Speed and duplex (please check that the duplex is matched on both ends of the cable)  
- Encapsulation type  

**Interpretation**:  
1. Look for "up up" in the first line so that it's working up to the second layer.  
   - If there is an issue in Layer 1/2, there will be "up down."  
   - If the line is shut down, it will be "down down."  

**Causes that cause the line to be down down**:  
- Administrative shutdown  
- Cable disconnection or failure  
- Poor line/signal quality  
- Speed or duplex mismatch  
- EtherChannel negotiation failure  
- Encapsulation (Layer 2 protocol) mismatch  
- VLAN mismatch  
- STP port blocking  
- PoE overload  
  - End device pulls more power than switchport can deliver  

It could be that the port is not plugged in or in use.
