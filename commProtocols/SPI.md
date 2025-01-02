# SPI (Serial Peripheral Interface) #
* Full Duplex Communication (Master-Slave Transmission and Recieving can take place simultaneously
* CS (Chip Select Line) is a disavantage of SPI, as it hoards GPIOs. CS is high by default, when Master needs to talk to that particular slave, it will pull that clock select line to ground.
* Defacto Communnication, hence no standard frame.

![image](https://github.com/user-attachments/assets/4e032977-ccf1-41ad-8c98-6467b203e5e8)

MOSI: Master Out Slave In
MISO: Master In Slave Out

## Modes of SPI Communication ##

### Clock Polarity ###
![image](https://github.com/user-attachments/assets/e7706b78-1bfc-4b66-a0a8-ed8dc6b1afbd) 

### Clock Phase ###
![image](https://github.com/user-attachments/assets/2017ed8a-9e47-478e-9126-a1c2037cade1)
![image](https://github.com/user-attachments/assets/3dfcc554-66b6-4ec8-93d9-939b16eeac84)



