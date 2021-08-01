# PC case temperature 7 segment display

** This description is not yet complete. Schematics and some more detailed pictures I still need to add... will be done soon. **

** This project allows you to show your PC case temperature on a 4 digit 7 segment display connected to an Arduino NANO **

</br>
<img src="https://i.imgur.com/EwXUg77.png">

It has been tested sucessfully with following setup:

* Windows 10 x64

* Arduino IDE 1.8.16

* Arduino NANO (other Arduino boards work as well with some modifications depending on the model)

## Prerequisites for the Arduino part of the project

* [Arduino IDE](https://www.arduino.cc/en/software) installed

* Flash the KTY81-110_7segm.ino file to the Arduino NANO

* Connect the Arduino via USB to your PC

## Required hardware components:

      7 segment display with 4 digits (common anode type)
	  1x 8bit shift register 74HC595
	  1x Resistor xxx Ohm
	  1x Resistor xxx Ohm
      KTY81 110 temperature sensor
      Arduino NANO
      
Check the schematic below to see how the components need to be connected to the Arduino NANO:

      xxx
	  xxx
	  xxx
	  to be continoued...

<b>Click to enlarge:</b> 
</br> </br>
<img src="https://to_be_done.png" width="600">


## Check the temperature on the serial line (COM port)

* As soon as the Arduino is powered up it will continously send the calculated resistance value and the temperature accordingly over the serial line via the USB the Arduino is connected to. It can be read off by connecting to the COM port with e.g. the Arduinos serial monitor, putty or any other serial monitor you're familiar with.
      
* The COM port your Arduino is connected to can easily be found by checking your Windows device manager or by looking in the Arduino IDE.
  
</br>

<img src="https://to_be_done.jpg">

</br>

<img src="https://to_be_done.jpg">