
# Portenta Board Micropython Examples


## Abstract
_Micropython is a relatively new technology in the fields of IoT and Robotics. It accelerates projects prototyping. In this project, a new set of examples will be written for beginners and for those who are new to robotics. In addition to providing various examples for many libs. supported by Arduino to make it well documented in Micropython world._

## Technical Details

_Micropython examples can be divided into 4 main categories (Basics - Communication Protocols - Network - Robotics) in each category a set of examples will be provided_

#### **Basics Examples**
_consists of intro to upython as a language and basic operation can be made by the board_
- Print Hello world
- Led examples blinking 
- Digital input examples
- Get input from Console
- Analog write/read
- os module (files i/o - create directories)
- Various motors Examples (DC motor - servo motor - brushless motor - stepper motor)
#### Communication Protocols & Various Sensors Examples
_consists of examples for communication protocols (UART - I2C - SPI) and sensors that uses this protocols like (Magnetometer - IMU - Barometer - External ADC - SD Card)_

- UART Example (serial input)
- Uart to communicate with another arduino
- I2C sensors examples (variety of i2c devices like bmp180 - pcf8574 - pca9685)
- SPI devices examples (sd card)
- Display Screen (LCD - tft touch screen - etc.)

#### Robotics Category
_Consists of examples related to robotics like (PID control - Line following robot - ROS communication)_

- RC car Prototype
- wall follower Prototype
- line follower Prototype
- ROS examples (topics - msgs - srv)
- interfacing ROS with rc car prototype

#### Network Examples
_consists of examples related to IoT like (HTTP web server - MQTT Server - WiFi communication - fire base)_

- WiFi communication
- HTTP server/client
- Fire base DB
- Use online services like (weather services - sending sms - etc


###### Note : The demonstrated examples aren't the final list to be implemented. This list contains the sensors i have right now. At the summer i could buy or borrow more sensors to implement,
### Project Hub Examples
- Getting started with the board and print hello world
_Robots made in Robotics category will be made as Hardware prototypes (RC car - Wall follower - Line follower)_

## Schedule of Deliverables

_As mentioned in the technical details section deliverables can be divided into different phases_

**Community Bonding Period**: During this period I will get use to the new board, prepare the sensors and the hardware required for the project

**First Milestone** : _In this milestone, the first set of examples (Board Basics) will be delivered and it's estimated to be delivered in a week_
| Day  |                           Example to be Delivered                          |
|------|:--------------------------------------------------------------------------:|
| 18/5 |  Getting started with the board in Project Hub & Print Hello world Example |
| 19/5 |                Led Examples (Turn on a LED - Blinking Led)                 |
| 20/5 |           Digital Input (use a push button to Turn on/off a LED)           |
| 21/5 |       Get input from Console (use input keyword) to turn on/off a LED      |
| 22/5 | Analog read/write (use a potentiometer to control a LED) - RGB LED Module  |
| 23/5 |       Micropython OS module example (file i/o - directory navigation)      |
| 24/5 | Motors examples (stepper motor - servo motor - brushless motor - dc motor) |

**Second Milestone** :  _In this milestone the Second set of examples (Communication & Sensors Examples) will be delivered and it's estimated to be delivered in (3 weeks) depending on the sensors available for me to interface and if it has a micropython libs. available or I have to write it from scratch_
| Day               |         Example to be Delivered        |
|-------------------|:--------------------------------------:|
| from 25/5 to 14/6 | Communication Protocols & Sensors libs |

**Third Milestone** :_In the third milestone the third set of examples (Robotics examples) & the Hardware prototypes will be delivered and  it's estimated to be delivered in (2 weeks)_
| Day               |                                 Example to be Delivered                                |
|-------------------|:--------------------------------------------------------------------------------------:|
| from 15/6 to 28/6 | Hardware prototypes for RC car - Line follower working with standard code and with ROS |

**Fourth Milestone** : In the Final milestone the last set of examples (IoT & Internet Examples) _will be delivered and  it's estimated to be delivered in a Month_
| Day               |                                Example to be Delivered                               |
|-------------------|:------------------------------------------------------------------------------------:|
| from 29/6 to 19/7 | Various IoT and Network examples like Tcp server - http server - firebase app - etc. |

**Bonus Phase** : In this milestone,I will learn more about tensorflow in micropython then a set of tensorflow lite examples will be provided depending on the adaptability of tensorflow with micropython_ 

| Day               |                        Example to be Delivered                        |
|-------------------|:---------------------------------------------------------------------:|
| from 19/7 to 10/8 | Learning more about tf in upython then creating basic examples for tf |

###### Note : Concerning other milestones, if libraries aren't available I'm willingly can implement them but it may be difficult using tensorflow.
###### Note : The demonstrated examples aren't the final list to be implemented. This list contains the sensors i have right now. At the summer i could buy or borrow more sensors to implement,

## Development Experience
#### My Experiences : 
-   Python & micropython
-   solid experience in raspberry pi - esp8266/32 boards
-   good knowledge in software engineering concepts
-   Java, JS, HTML, CSS
-   C/C++ (QT framework)
-   Verilog
#### Projects : 
In my github there are several examples written by micropython and several libs In addition to  general microcontroller projects in C 
 -  HTTP server (implemented in micropython) [WebServer](https://github.com/mgtm98/Nodemcu-WebServer)
 - [uRos](https://github.com/mgtm98/uRos) (ros implementation to run in micropython 
 - feedback system written in micropython  for ROV (remotely operated vechial) that saves logs from motors and other sensors in json format in SD-card and display samples pf them in a live stream Server (TCP Server - QT GUI) [ROV feedback system](https://github.com/ASURT-ROV-20/Embdded), [ROV-20](https://github.com/ASURT-ROV-20)
 - Several projects related to ARM development (Tiva-c) [Tiva-C firmware](https://github.com/3rd-year-CSE-20/ARM-TM4C123-Safe-Project/tree/Gemy_Modifications)
 - Many Robots ( RC car - Line follower - Wall follower ) implemented in Arduino 


## Other Experiences

 - I  was an organizer & Technical Support Team Head in a robotics competition held at the faculty campus (Ain-Shams University - Faculty of engineering)
 - ROV software member in Ain-Shams University Racing Team (we were participating in mate Competition this year but unfortunately it was canceled due to COVID-19 virus)



## Why this project?
_First of all Arduino  helped me to get started with microcontroller world so it will be an honor to contribute in this project._
_Besides that I chose this project as I am very passionate about using micropython as it helps non engineering students and hobbyists to create and innovate_

## Do you have any other commitments during the GSoC period?

_My exams will take place from 27th of May to 30th of June, so I won’t be able to work with my full capacity for about fifteen days, but I’m going to make it up in the following months of the project._

