# Smart-Carry-Bagpack

![Smart Backpack](https://user-images.githubusercontent.com/75977813/236689877-5417d839-6055-430e-91b0-121daa0b86f8.gif)

## Components used

- Force Sensing Resistor
- Force Sensor
- Arduino UNO
- 22K ohm Resistors
- Buzzer
- Bluetooth Module
- Jumper Wires

The circuit is Rigged as shown in the circuit diagram below

![Circuit](https://user-images.githubusercontent.com/75977813/236690586-a62b3379-daa5-4395-a8cc-c5685e743084.png)

### Connections 
#### FSR and Force Sensor
- One of the lead of the FSR is connected to the 5V pin in Arduino.
- The other lead of the FSR is connected to the 22K resistor and the resistor is connected to the GND pin of the arduino.
- The lead is also connected to the A0, A1, A2 pins of the arduino ( A0 -> Middle sensor, A1 and A2 pins are from the strap ).
#### Buzzer
- The positive lead of the buzzer is connected to pin number 7.
- The negative lead is connected to the gnd pin of the arduino.
#### Bluetooth (HC-05)
- RX pin is connected to TX pin of arduino. 
- TX pin is connected to RX pin of arduino. 
- VCC pin is connected to the 5V terminal of the arduino.
- gnd is connected to the gnd of arduino.



