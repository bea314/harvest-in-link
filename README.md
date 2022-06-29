# Harvest in Link
IoT Plant Sensor

## Introduction
The product aims to solve the need to monitor the state variables of a garden via wifi with the possibility of automatically controlling the water with an extra module. On the other hand, the device was detailed and sistematically designed.

## First Stage - System Level Design

![Systems](https://user-images.githubusercontent.com/60575708/162120550-7ad3462b-57a7-46d2-836e-dc2c9833f088.png)
*Defining all possible systems.*

![Functions](https://user-images.githubusercontent.com/60575708/162120905-593bfc53-1c61-4fe2-ada2-ad21438210d3.png)
*Function clustering.*

![Geometric Arrangement](https://user-images.githubusercontent.com/60575708/162121421-63a1b6df-e478-4ff3-97dc-ef822c3fb863.png)
*Approximate geometric arrangement.*

## Second Stage - Collection of customer requirements

### Interviews
The interviews were answered by 66.7% women and 33.3% men, of whom the average age was 22 years. 86.7% were single and 80% earned the minimum wage. But most importantly, 73.3% of them identified with the problem.

Several comments highlight different problems with water. Some mention that the scarcity of water in the housing area; and therefore, the scarcity of water to irrigate causes the plants to suffer and not bloom as they should. They also emphasize that they try to make the most of their water resources.
In addition, they also mentioned that they use constant surveillance and manual operations to take due care of the plants.

However, they only experience these problems 13.3% daily. Which are 46.7% very important and 40% important.
Currently, the interviewees solve their problems by being self-taught and using manual but functional tools. However, most of the interviewees do not have a way to solve their problems.

According to the solutions used by some of the interviewees they find 3 different problems:
- The lack of time prevents the constant application of the necessary supervision.
- It is necessary to make a high investment for each need.
- Technologies are not 100% effective.

Most of the interviewees suggested that the solution would be to automate the crop care system. Among the functions mentioned we have an irrigation system and surveillance of the circumstances of the plantation.

In addition, 40% believe that to solve this problem it would be necessary a new product on the market. Which should have the following characteristics:
- Effective.
- Cheap.
- Trustworthy.
- Simple and intuitive.
- Easy access.
- Small and accessible for home gardens.
- Wireless (IoT).

### Quality House (QFD)
**[QFD Link](https://udbedu-my.sharepoint.com/:x:/g/personal/vo160635_alumno_udb_edu_sv/Ed4N0Y6Tv6VBovyXYLu_prwB2Ia1L9plpPGh_5FZ8eRGlQ?rtime=h4sAStEy2kg)**


Based on the information collected, the following questions can be answered:


***What characteristics are most important according to the client or user?***
The user prefers an economical, easy-to-use system that automates the control and visualization system of the variables presented when growing plants.

***What technical characteristics are of greatest importance to the organization?***
AAD prioritizes intuitiveness of device usage, appearance, and real-time communication.

***What characteristics should be taken according to the comparison with the competitor?***
The following features should be prioritized:
- Remote monitoring in real time.
- Intuitive visualization and control interface.
- Alert system and wireless control according to the needs of the crop.

### Concept Designs
In this section we will focus on detailing the systems: “case”, “power supply”, “processor”, “actuators”, “interface” and “variable measurement”. This section allows to provide more detailed information of the selected elements and for the easy obtaining of these and local market delivery time.

***Case***

It is important to achieve protection against dust and water, being desirable to have a degree of protection IP68 (dustproof and protection against staying under water). However, a protection achievable by the IP64 prototype (dust-proof and splash-proof).

- Design in Fusion 360.
- Plastic material. 3D printing (PLA / ABS / Resin).
- Stove screws 3x6mm.
- Rubber gaskets.

***Power supply***

An important feature of this system is its portability.

- 18650 lithium battery.
- Battery charger (18650 shield v3).

***Processor***

The selected processors have a built-in Wi-Fi module.

*Hardware:*

- Option 1: ESP32.
  
- Option 2: ESP8266 NodeMCU ESP-12E.

*Firmware:*

- Development environment: Arduino IDE.

***Actuators***

- 2 relay modules 5VDC.
- 1 fan.
- 1 solenoid valve or 1 water pump system.

***Interface***

The interface was selected taking into account that the means of communication would be Wi-Fi and that the user could view their information from an intelligent device such as cell phones or computers.

- Option 1:
  - Docker (local server / simulated server environment).
  - Flutter (Framework for the development of mobile applications with Dart).
  - MQTT communication protocol using RabbitMQ within Docker.
- Option 2:
  - Blynk (facilitator platform of the MQTT IoT protocol).

***Variable measurement***

- Environmental temperature and humidity sensor (DHT11).
- Capacitive moisture sensor (soil) v2.0.
- pH sensor with probe.
- *(Optional)* LDR light sensor.

## Third Stage - Electronic, mechanic and computational Design
To carry out the electronic design of this project, the Eagle software was used, which is a CAD design tool, which has an extensive library or libraries from which the electronic components necessary to develop this project have been selected.

It is important to clarify that for the implementation of the project it has been considered to separate the components into two different modules, each one independent of the other, but which will always be linked to have an exchange of data between the IoT platform.

WIP

## Fourth Stage - Test and prototype
WIP

### BOM
WIP

## Conclusion
WIP

## References
Youtube.com. 2022. Blynk Home Automation with Multiple ESP8266 Boards. [online] Available at: <https://www.youtube.com/watch?v=CT9PotokFbo> [Accessed 1 May 2022].

Youtube.com. 2022. Capacitive Soil Moisture Sensors don't work correctly + Fix for v2.0 v1.2 Arduino ESP32 Raspberry Pi. [online] Available at: <https://www.youtube.com/watch?v=IGP38bz-K48> [Accessed 1 May 2022].

Youtube.com. 2022. Cómo programar ESP8266 con el IDE de Arduino. [online] Available at: <https://www.youtube.com/watch?v=0g7sazWXfEI> [Accessed 1 May 2022].

