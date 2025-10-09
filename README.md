# ishan_sonar
Dec 7 2022, Freshman Year Project
This is a 160 degree sonar-model, that works by sensor integration by the arduino: HC-SR04 the ultrasonic sensor, and servo motor, arduino nano; the arduino code is to control the parts, while the Processing IDE code is to develop the visual interface, the code for the processing IDE has been reproduced from robu.in website: https://robu.in/arduino-radar-project-ultrasonic-based-radar-connection-and-code/

The 160° Sonar System is an Arduino-based radar visualization project that uses an ultrasonic sensor mounted on a servo motor to scan an area and display distances on a Processing GUI. The servo sweeps across a 160° field of view, and the ultrasonic sensor measures distances to nearby objects. The Arduino sends these readings to Processing via Serial, where they are displayed as a radar-style visual.

Required:
Arduino Nano
HC-SR04 Ultrasonic Sensor
-The HC-SR04 ultrasonic sensor works on the principle of echolocation, similar to a bat. By emitting a high-frequency sound pulse and measuring the time it takes for the echo to return, the sensor can calculate the distance to an object. 

SG90 Servo Motor
Jumper wires
USB cable (for PC connection)
(Optional) Breadboard and power supply

Notes:
Adjust the COM port in the Processing code ("COM3") to match your system.
The sweep range can be modified in the Arduino code.
Ensure the servo and sensor share a common ground.
You can tweak the delay or drawing speed for smoother performance.

Disclaimer: Parts of this project were assisted by AI tools
