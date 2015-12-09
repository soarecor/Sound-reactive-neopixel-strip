# Sound-reactive-neopixel-strip
This tutorial will highlight how to take sound output from the audio jack of a computer or phone and use the outputted signal to make a WS2812 led neopixel strip illuminate responsively. This code uses a total of 90 neopixels in the led strip. The code is adapted from "such builds" youtube video and code.
https://www.youtube.com/watch?v=0PgFK85fIHM

To connect to the audio jack I am using a double sided stereo cable connected to crocodile clip wire. It is important to attach the crocodile clip to either the first or second "rung" on the stereo cable, since these correspond to the left and right channels respectively. Please refer to the images below in the directory.

Connect the black wire from the neopixel to the ground input from the neopixel first. Connect the red wire from the neopixel strip to the 5V input on the arduino. Connect the green wire to digital input 6 on the arduino.

Load the arduino sketch. Ensure the correct usb port is selected before uploading the sketch. Upon playing any song the led strip should flash accordingly to the audio output.
