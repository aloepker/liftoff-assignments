# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
So I'm excited to help the real world come alive through the use of technology! My is to take a temperature and humidity sensor and connect it to an arduino, which will then send data to a nodejs server to be updated on a webpage in realtime. The realtime temperature data can then be used in equations, graphed or stored in a database. My motivation was wanting to see inputs from an indoor garden remotly. In the future this project can include the ability to remotly turn on fans and adjust water timers. Realistically there is a lot of expansion potential.

### Features (3-5)
1) Arduino sensor input - Arduino will be running code to capture data from a temperature sensor and broadcast that data via serial connection.

2) NodeJS Websocket Server - The server will host the arduino's serial data to a webpage via serialport & websocket npm packages.

3) Web page - will display the imported data from websocket on a webpage in realtime and also be able to calculate an equation with imported data.

### Technologies
eMakeFun offbrand Arduino Nano plc boards
a local network (wifi & ethernet)
A Web Browser Running JavaScript
Arduino Language (C++ Hybrid)
LinuxMint Terminal
JavaScript/NodeJS
HTML/CSS
Apache2

### What I'll Have to Learn
node packages serialport and websocket
some c++/arduino language
a few LinuxMint commands and app/package instalations

### Project Tracker
https://trello.com/b/uB0vbUxp/arduino2nodeserver2webpage  
