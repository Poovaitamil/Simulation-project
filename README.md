# TITTLE:
Smart Irrigation System using arduino UNO
## ABSTRACT:
The key objective of this project is to monitor the soil’s moisture content during its dry and wet conditions with the aid of a moisture sensor circuit, calculate the corresponding relative humidity and irrigate it based on its nature using Arduino, Soil moisture sensor, Ultrasonic sensor, GSM and an automatic water inlet setup which can also monitor and record temperature, which is constantly modified and can be controlled in future to optimize these resources so that the plant growth and yield is maximized.
## INTRODUCTION:
Aim is to develop a smart irrigation system to provide irrigation system which is automatic for the plants which help in saving water and money. Fields should neither be over-irrigated nor under-irrigated. The objective of this thesis is to design a simple, easy to install methodology to monitor and indicate the level of soil moisture that is continuously controlled in order to achieve maximum plant growth.

The Arduino UNO can be programmed to analyze some signals from sensors such as moisture, temperature, and rain. A pump is used to pump the fertilizer and water into the irrigation system. The use of easily available components reduces the manufacturing and maintenance costs.
## LITERATURE REVIEW:
In [1], the paper emphasizes about the essentiality of water for human beings, plants and animals. The key aim of the paper is to reduce human intervention to reduce percentage water wastage in agricultural farms using a water level controller with wireless technology. The paper has said about the development of 4 stages of water pumping system. The paper has also compared between the wired and wireless Bluetooth based water level controller. They have used an Ultrasonic sensor, Arduino uno microcontroller, pump, relay and Bluetooth module HC-12. The controller decides unique code for water level based on 4 stages of water pumping. Distance is calculated using formula d=S*(T/2)=0.03435*(T/2), where S is speed of sound, T is duration of transmission and reception of sound wave from an ultrasonic sensor. S=0.003435 cm/microsecond.
The paper also displays drawbacks of wired controller, which includes limited wire length, which paved way for introducing wireless automatic water level controller. In [2], the paper says about the issue due to excessive water usage in the domestic or commercial purposes, which in turn may lead to further problems like problem with weather patterns. The paper has said about the development of a system comprising of a water level sensor, digital logic processing unit or integrated circuit(IC), for input signal processing, 7 segment display, JK flip flop sequential circuit, motor driver controlled by relay. The data from the water level sensor is encoded using a digital encoding circuit, where water level is encoded to decimal, indicating the water level from 0 to 9. The decimal is then decoded from BCD to 7 segment using BCD to 7 segment decoder (IC7447). Digital logic controller, responsible for the turning on or off of the pump, turns the pump whenever the water level reaches ONE, and turns off when it reaches level NINE. A JK flip flop is used as a driver circuit to turn on or off the motor. Relay is used as a switch, which turns on the International Journal of Engineering Research & Technology (IJERT)ISSN: 2278-0181http://www.ijert.orgIJERTV9IS070458 (This work is licensed under a Creative Commons Attribution 4.0 International License.)Published by :www.ijert.orgVol. 9 Issue 07, July-20201092 motor and also turns it off whenever the tank reaches full capacity.
## PROPOSED METHODLOGY:
Internet of Things with ESP8266 The Internet of Things has two keywords, internet and things. Internet, which stands for interconnectionnetworking, is a network of the computer that connect to each other using TCP/IP (Transmission Control Protocol/ Internet Protocol). Things in the Internet of Things are the object that we use daily where the information of that things retriever from sensors that read environment around in real time without human intervention. Such as room temperature, humidity, and pressure. So Internet of Things means objects that can generate data through sensors and the data sent to the server or computer via the internet connection. The Internet of Things is also very closely related to the communication Machine to Machine (M2M) that can communicate without any human intervention in it [1]. Internet of Things is also the first step in making Smart World where mixing of data from objects and smart city [2]. The Internet of Things has 3 crucial component:

A Hardware that consist of sensors, actuators, microcontroller and communication device.
A Middleware that consists of data storage a data analytic capability.
A presentation that consist of easy understand visualization data from middleware and provide useful information. Firstly the Ultra Sonic sensor reads the level of water tank, converts it into scale of 100 and sends the data to Arduino. Similar for Soil moisture sensor. It reads the water content of soil, converts it into 100 and sends the data to Arduino. In Arduino it analyses the data received from UltraSonic sensor and Soil moisture sensor. Arduino operates their respective Motors as per their threshold levels of Water tank level and Soil moisture. Prints the Output in LCD.
## CIRCUIT DIAGRAM:
![image](https://github.com/Poovaitamil/Simulation-project/assets/132209885/0bed7874-c9a3-4a66-9ead-c6d45878aed3)

## PROGRAM:

## RESULTS:
![out](https://github.com/Poovaitamil/Simulation-project/assets/132209885/2250f0b4-3f3c-4377-9709-349ea631ac76)

## CONCLUSION:

## REFERENCE:

