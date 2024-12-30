# Topologies of Communication #
* ### Bus Topology : ###
 All the devices get connected to a common bus where they need to talk to each other throught the 
 bus. If they need to communicate with all the devices, it will broadcast. If one of the devices 
 is disconnected, still all the other devices are able to communicate. Example: CAN
 ![image](https://github.com/user-attachments/assets/b881e992-4053-4bb1-bf7d-4dbc0840c405)

* ### Star Topology : ###
 One Master connected to all slaves. Only Master talks with slaves.
 ![image](https://github.com/user-attachments/assets/abe8e79c-382c-459b-a30c-aa53ff11c542)

* ### Ad-Hoc/Peer To Peer Topology : ###
 Two devices talk to each other. Example: UART
 
 ![image](https://github.com/user-attachments/assets/a2f6add2-5b93-4e45-9ca1-087e592b5430)

# UART #
UART is a character oriented protocol that means data is sent byte by byte. The RX (Reciever) of Device 1 is connected to TX(Transmitter) of Device 2 and vice-versa.
* Lines are High by default, the start bit pulls them low

### Data Frame ###
The data frame consists of a start bit, 8 data bits, a parity bit and a stop bit
![image](https://github.com/user-attachments/assets/663319a3-d2e6-40ed-a517-3f36668dd15a)

### RS232 ###
* 9 pin connector
* Multiple handshakes to prevent data loss
* 1's: -3V to -25V
* 0's: +3V to +25V
* ![image](https://github.com/user-attachments/assets/de17f49f-4032-4c04-b223-29c9f0a36dee)

### Programming Approach ###
* #### Bit Banging ####

