# Sound-reactive-neopixel-strip
This tutorial will highlight how to take sound output from the audio jack of a computer or phone and use the outputted signal to make a WS2812 led neopixel strip illuminate responsively. This code uses a total of 90 neopixels in the led strip. The code is adapted from "such builds" youtube video and code.
https://www.youtube.com/watch?v=0PgFK85fIHM

To connect to the audio jack I am using a double sided stereo cable connected to a crocodile clip wire. It is important to attach the crocodile clip to either the first or second "rung" on the stereo cable tip, since these correspond to the left and right channels respectively. Please refer to the images below in the directory.

Connect the black wire from the neopixel strip to the ground input on the arduino first to ensure safety. Connect the red wire from the neopixel strip to the 5V input on the Arduino. Finally, connect the green wire to digital input 6 on the Arduino.

Since the power output from the usb port is not enough to power 90 neopixels, an external power supply is needed. I am using a 9V 210 mA power supply for to supply additional power. Arduino recommends using a minimum requirement is 9V 250mA. However, since I am also supplying power from the usb port connected to the Arduino, the 210 mA adapter was sufficient. For more guidelines on how to select an appropriate power supply please refer to this arduino guideline. http://playground.arduino.cc/Learning/WhatAdapter

Load the arduino sketch. Ensure the correct usb port is selected before uploading the sketch. Upon playing any song the led strip should flash accordingly to the audio output.
