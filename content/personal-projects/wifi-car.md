+++
date = '2024-04-01T11:51:07+08:00'
draft = false
title = 'ESP8266 Based WiFi Controlled Two-Wheeled Car'
+++

# Introduction
This ESP8266 based WiFi controlled two-wheeled car consists of a two-motored, two-wheeled car platform controlled by an ESP8266 microcontroller. Client devices such as mobile and desktop devices can be connected to the ESP8266's WiFi hotspot so that the user can view the status of the different parts of the car and control the movement and state of the car via the web browser on the connected device. 

# Rationale
I created and worked on this ESP8266 based WiFi controlled two-wheeled car first and foremost because I have always wanted to design and create my own RC vehicle ever since with mechanical components, electronics components, and code. With the popularity of WiFi-equipped microcontrollers such as the ESP8266 and smartphones, I found this project to be a good starting point to familiarize with ESP8266 microcontroller development in the Arduino platform. Specifically, I wanted to learn the multiple technologies, frameworks, and languages that I need to integrate when creating a simple RC car system. Some of the topics I learned and applied are the ESP8266 microcontroller and its WiFi stack, realtime websocket communication, HTTP webserver, basic front-end web development, and creating a simple mobile robot with a body, motors and motor controllers, battery packs, microcontroller, remote control system, sensors, and miscellaneous electronics like LEDs and buzzers. 

# Features 
These are the features of this ESP8266 based WiFi controlled two-wheeled car:
- Powered by 2S li-ion battery
- Off the shelf car chassis and gearmotors
- Controllable by any device with WiFi and a web browser
- Controlled via websockets sent from the web based user interface 
- Front and rear LED headlamps and taillamps, and a buzzer as a horn

# Current Status

# Things to Improve

# Related Blog Posts



, which facilitates the movement of the car, switching miscellaneous electronics such as LEDs and a buzzer, serving a WiFi hotspot for clients to connect to, serving the user interface webpage to the browsers of connected devices, handling real-time websocket communication, and taking readings from the ultrasonic sensor. Once the car is powered on by connecting the battery pack connector, the ESP8266 serves an open WiFi hotspot for client devices such as mobile and desktop devices to connect. Once a client device connects to the ESP8266, the user interface can be accessed on the browser of the connected device. 



