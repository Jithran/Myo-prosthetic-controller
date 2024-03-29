## Myo prosthetic arm controller

The e-NABLE Community is an amazing group of individuals from all over the world who are using their 3D printers to create free 3D printed hands and arms for those in need of an upper limb assistive device.

This code is for an automated arm trigger with a muscle sensor with servo activation.

We use a MyoWare Muscle Sensor for this project, but any EMG sensor will suffice.

### Installation
Compile the Arduino code to an Arduino compatible board (we use a attiny85)
Pinout for muscle sensor, button, RGB led and servo control can be found in the
Arduino code.

### Credits for used libraries:
- Bounce2 for button debounce (https://www.arduinolibraries.info/libraries/bounce2)
- MsTimer2 for periodically function triggers (https://www.arduinolibraries.info/libraries/ms-timer2)

### License
This project is released under a GPL License.

### Credits and Contributors
- Jithran Sikken - Author
- Sander Podt for his help with prototyping and debugging
- Irfanmohamed12 - for initiating this project
