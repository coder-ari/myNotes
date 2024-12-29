#Topologies of Communication#
*Bus Topology
 All the devices get connected to a common bus where they need to talk to each other throught the 
 bus. If they need to communicate with all the devices, it will broadcast. If one of the devices 
 is disconnected, still all the other devices are able to communicate.
 Example: CAN
 ![image](https://github.com/user-attachments/assets/b881e992-4053-4bb1-bf7d-4dbc0840c405)

*Star Topology
 One Master connected to all slaves. Only Master talks with slaves.
 ![image](https://github.com/user-attachments/assets/abe8e79c-382c-459b-a30c-aa53ff11c542)

*Ad-Hoc/Peer To Peer Topology
 Two devices talk to each other. Example: UART
 ![image](https://github.com/user-attachments/assets/a2f6add2-5b93-4e45-9ca1-087e592b5430)

#UART#
UART is a character oriented protocol that means data is sent byte by byte. The RX (Reciever) of Device 1 is connected to TX(Transmitter) of Device 2 and vice-versa.
*Lines are High by default

###Data Frame###
![image](https://github.com/user-attachments/assets/d007d6af-9768-4277-80f3-609c61ff0296)

