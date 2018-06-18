# Maslow Electronics Setup

We've done our best to keep the electronics for Maslow as simple as possible.

### Step 1: Identifying Parts
There are five pieces to the Maslow electronics system. Shown in the picture below from left to right and top to bottom they are:
1. The Motor/Encoder/Gear Box Units
2. Motor Wires
3. Maslow CNC motor controller shield
4. Keystudio Mega 2560 microcontroller (Arduino compatible) with USB Cable
5. 12V DC 5A / 110-250V AC Power Supply
![Identifying Parts](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Identifying%20Parts.jpg)

### Step 2: Attach Heatsinks
Attach the sticky backed heat sinks found in your hardware bag to the motor controller shield. (Note orientation of heatsinks)
![Attach Heatsinks](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Attach%20Heat%20Sinks.jpg)

### Step 3: Connect Arduino Shield
Attach the Arduino shield onto the Keystudio Mega 2560 microcontroller. Make sure all the pins are not twisted and that are aligned with the microcontroller before pushing the motor controller shield.
![Attach Arduino](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Attach%20Arduino.jpg)

### Step 4: Connect The Motors
Attach the motors to the motor controller shield. **Note that the motors connect to ports 1 and 3 not 1 and 2**. This is to better distribute the motor power draw across both motor driver chips.  Port 3 controls the left motor and Port 1 the right motor (as viewed when facing the MaslowCNC).
The cables have two sides, so make sure that when plugged in the Arduino shield, the yellow wire is at the bottom in both ports as seen in the following photo.
When using the optional Z axis, this motor is connected to port 2.

![Attach Motors](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Attach%20Motors.jpg)

### Step 5: Connect The Power Supply
Plug the 12V power supply into the motor controller shield. **Note that the power supply plugs into the motor controller shield and not to the microcontroller.** Plugging the power supply into the Arduino will not damage it, but it also will not provide power to the motors. We chose the most common power supply plug to make replacements easy to find, unfortunately because it is so common this is also the same power supply plug that the Arduino uses, which is somewhat confusing.
![Attach Power Supply](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Attach%20Power%20Supply.jpg)

### Step 6: Connect The USB Cord
Plug the USB cord into the Arduino and into your computer. Note that the "USB" light will come on to indicate that the board is connected and receiving power from your computer.
![Attach USB](https://raw.githubusercontent.com/MaslowCNC/Electronics/master/Documentation/Attach%20USB.jpg)

### Step 7: Proceed
You have finished setting up the Maslow electronics system. Proceed to the [next step](http://maslowcommunitygarden.org/Firmware.html?instructions=true) and install the open source Maslow Firmware on your Arduino.
