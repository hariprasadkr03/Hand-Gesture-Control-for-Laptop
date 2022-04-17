# Hand-Gesture-Control-for-Laptop
## Introduction
Vision and gesture are playing a crucial role in establishing communication between humans and computers just like physical devices (keyboard and mouse) do. There are various ways available for establishing communication between humans and computers. Out of those techniques, the hand gesture is very easy and fast to perform operations done by keyboard and mouse. Hand gestures can be implemented in various ways by using IR sensors, digital cameras, color bands and ultrasonic sensors. Each technique has its advantages as well as disadvantages. But out of all given techniques, using ultrasonic sensors is considered to be more comfortable as well as faster.

Human Machine Interface or HMI is a machine comprising of hardware and software program that enables in communication and change of records among the user (human operator) and the machine. Instead of using standard input devices like a keyboard, mouse or joystick, we can use hand gestures to govern certain capabilities of a laptop like play/pause a video, move left/proper in a photograph slide show, scroll up/down in an internet page and plenty of more. In this venture, we have implemented a simple Arduino based hand gesture control where you to determine the position of our hand and control Web browsing and a media player controls based on the position.
## Working
The principle behind the Arduino based Hand Gesture Control of Computer is actually very simple. All you have to do is use two Ultrasonic Sensors with Arduino, place your hand in front of the Ultrasonic Sensor and calculate the distance between the hand and the sensor. Using this information, relevant actions in the computer can be performed. The position of the Ultrasonic Sensors is very important. Place the two Ultrasonic Sensors on the top of a laptop screen at either end. The distance information from Arduino is collected by a Python Program and a special library called PyAutoGUI will convert the data into keyboard click actions. There are many gestures which can be set, any “Keyboard shortcut” can be saves as a hand gesture.

Some examples are:

• Place your hand in front of both the Ultrasonic Sensor at a distance (between 40CM to 50CM) for a small duration. This gesture plays or pauses the video (control the space bar).

• Place your hand in front of the Right Ultrasonic Sensor at a distance (between 13 to 17 cm) for a small duration and move your hand towards the sensor. This gesture used Volume variation, switching tabs, scrolling up and down, even games.
## Requirements
### Hardware Requirements:
• Arduino UNO x 1
• Ultrasonic Sensors x 2
• USB Cable (for Arduino)
• Few Connecting Wires
• A Laptop with internet connection
### Software Requirements:
• Arduino IDE
• Python IDLE
• PyAutoGUI Library
### Simulation Video
[Video](https://drive.google.com/file/d/1eX_ybm2unucMyOcJHodgW-bIinYgMT90/view)
