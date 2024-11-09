 CAN Bus protocol ,Interfacing MCP2515 CAN Bus Module with Arduino. 
 We will transmit the DHT11 Sensor data over a certain distance using the CAN protocol.

Controller Area Network also known as CAN-BUS is a common industrial bus because of its long travel distance, 
medium communication speed, and high reliability. It is commonly found on modern machine tools and as an automotive diagnostic bus.

In modern Vehicle systems, there are more than 60 to 100 sensor units for sensing and exchanging information. 
Similarly, car manufacturers are constantly making their cars smarter by adding features like Autonomous driving, Airbag system, ABS (Anti-braking System), 
Telematics, Transmission Control, Battery management systems, Cruise control system, etc.
To enable the transmission and receiving of the data at a very high-speed standard automotive communication protocols are required. 
The standard communication protocols like UART, SPI, and I2C are not reliable for this system. Hence we need an automobile
communication protocol like the CAN protocol for high-speed & 1000s of data transmission at a single time.

CAN Bus Communication protocol using Microchip MCP2515 CAN Bus Module & Arduino Board.
Using the pair of CAN Bus Module MCP2515, we will send the DHT11 Sensor data over a distance of a few centimeters. 
Typically the communication speed for CAN ranges from 50 Kbps to 1Mbps and the distance can range from 40 meters at 1Mbps to 1000 meters at 50kpbs.


components required
1. Arduino UNO Board	  -2
2. CAN Module MCP2515	  -2
3. I2C LCD Display	    -1	
4. DHT11 Sensor	        -1	
5. Jumper Wires 	      -30	
6. Breadboard	          -2


pin connections of arduino and mcp2515

MCP2515 Pin -	Arduino Pin | 
   VCC	- 5V | 
   GND - GND | 
   CS	 - D10 | 
   SO	 - D12 |
   SI	 - D11 | 
   SCK - D13 | 
   INT	- D2  | 

Features and Specification of MCP2515:

1. Uses High-speed CAN transceiver TJA1050
2. Dimension: 40×28mm
3. SPI control for expanding Multi CAN bus interface
4. 8MHZ crystal oscillator
5. 120Ω terminal resistance
6. Has independent key, LED indicator, Power indicator
7. Supports 1 Mb/s CAN operation
8. Low current standby operation
9. Up to 112 nodes can be connected
