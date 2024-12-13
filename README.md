# myNotes
## Push,Pull Resistors

There are many types of logic levels:
Some of the common logic levels are 5V, 3.3V etc.

In 5V logic level, 
- A signal is regarded as 1 when the voltage is between 2.0V to 5.0V
- A  signal is regarded as undefined when the voltage is between 0.9V and 1.9V
- A signal is regarded as 0 when the voltage is between 0V to 0.8V 

![image](https://github.com/user-attachments/assets/7efee9d8-4dc2-4c58-8b60-dae1e779d861)
When the resistors are not present, the pins are floating and there can be any arbitrary voltage
present on the pins, which can lead to the undetermined state. 
When the resistors are pulled up, the pins are at 5V level hence the output is 1. The moment the switches are 
pressed, they are connected to ground and the inputs are 0V.

![image](https://github.com/user-attachments/assets/b7eaf8fb-5130-470f-a722-d8b7300d9158)
When the switches are not pressed, the resistors are grounded , thus the inputs are at 0. When they are pressed
the inputs chane to 5V, which corresponds to 1.

### Why resistor?
Without the resistors, shorting will happen when 5V is directly connected to ground.
