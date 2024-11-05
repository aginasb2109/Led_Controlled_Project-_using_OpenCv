Led Controlled Project Using Arduino and OpenCV


Project Explanation
This project allows you to control five LEDs using hand gestures, leveraging an Arduino Uno and OpenCV for real-time gesture recognition. By using a camera to capture video, OpenCV processes the frames to detect specific hand gestures and sends commands to the Arduino to turn the LEDs on or off.

Connections
The LEDs are connected to the following pins on the Arduino Uno:

LED1: Pin 8
LED2: Pin 9
LED3: Pin 10
LED4: Pin 11
LED5: Pin 12
Each LED should be connected through a resistor (220Ω) to limit the current and protect the LEDs.

How It Works
Camera Input: The camera captures video frames, which are processed by the Python script using the OpenCV library.
Gesture Recognition: The script analyzes the video feed to detect specific hand gestures (e.g., open hand, fist, pointing).
Control Logic: Based on the recognized gestures, the script sends serial commands to the Arduino.
LED Control: The Arduino listens for these commands and activates or deactivates the corresponding LEDs.

Gesture to turn off all LEDs: Close fist
This setup provides an interactive way to control the LEDs, showcasing the integration of hardware and computer vision technology.
