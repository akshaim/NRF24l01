Download libraries from https://github.com/maniacbug/RF24
      
-----------------------------------
Connection
-----------------------------------

Arduino Pin	|  NRF24L01 Pin
		|
Pin 9		| 	CE
Pin 10 		| 	CS(N)
Pin 11		| 	MOSI
Pin 12		| 	MISO
Pin 13 		| 	SCK
Pin 3 		|	LED via 1K resistor (For receiver)
Pin 7		|	Button	(For transmitter)

** Make sure that VCC of the NRF24L01 is connected to 3.3V of Arduino. DO NOT CONNECT 5V!! **

Follow the image http://www.bashmodulo.com/wp-content/uploads/2014/05/NRF24L01-Receiver.jpg

------------------------------------
Code
------------------------------------


All codes are for arduino IDE usage.

Experiment 1: Lighting an led using a remote switch
Transmitter_Basic_Switch application to be uploaded on transmitter and Receiver_Basic_LED to be uploaded on receiver. LED connnected to Pin 3 on receiver will turn on upon receiving data(111) from Transmitter.

Experiment 2 : Data Transmission
Receiver_Data_Transmission application turns LED ON/OFF depending on data transmitted from Transmitter_Data_Transmittion application from Analog Pin A0 connected to an LDR.


