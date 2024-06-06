## Adafruit Switchable USB Type A to C Breakout Board PCB

<a href="http://www.adafruit.com/products/5972"><img src="assets/5972.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Switchable USB Type A to C Breakout Board. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5972

### Description

We don't quite know what to call this doohicky - some folks refer to it as a [USB Condom](https://int3.cc/products/usbcondoms) but that's specifically for when the data lines on a USB port are disabled so that a device charges without data access. This board is a little more advanced: you can manually switch each of the 4 wires on or off for a variety of uses:

* If you want to have a 'charge only' device, simply switch the D+ and D- lines off
* For power monitoring, you can do high side (disable the V+ line) or low side (disable the GND line)
* For tapping into the USB signal, or monitoring the power voltage, keep all the switches on and probe the labelled pads on either side

With the onboard 4-DIP switch, you can flip to your heart's content. Only thing to note is the [C&K SDA04H1SBD](https://www.ckswitches.com/media/1327/sda.pdf) switches are technically rated for 5V 100mA  so we designed this for low-current-draw microcontroller project board hacking. (You could probably go a bit higher but don't tell anyone!)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
