# Automatic-Pump-And-Water-Level-Controller

## Introduction
*Water is the important natural resource that should be efficiently 
used . Our project ‘Automatic Pump and Water Level Controller’ 
uses the Arduino and Ultrasonic sensor. The Basic idea of the 
project is to ensure the proper use of water and reduce the 
wastage of water. This basic idea can be implemented in many 
fields and purposes such as irrigation in agriculture land and water tanks to prevent the overflow of water 
pump controlling water usage monitoring etc.*


## Working of the System

*All the components in the project are controlled by Arduino 
which is micro controller. The ultrasonic sensor finds the level of 
the water by finding the time for the wave emitted by the emitter 
which bounces from the surface of the water and is received in 
the reviver. It is then multiplied with the speed of the sound 
to find the level of the water. This distance is used to switch on and 
off the DC motor. When the water level is less than the reference 
the DC motor is switched on and pumps water, else if the water 
level is at the required level the DC motor is switched off. 
To indicate the working of the DC motor we use an LED. An NPN 
transistor is used to amplify the signal to the DC motor. An LCD 
screen is used to show the water level in percentage. The LCD 
also has a progress bar which increases and decreases as per the 
water level. A servo motor is used here to represent if the system 
is on or off by changing its hands position. A slide switch is used 
to switch off and switch on the system.*

## Group Members

- [@Arjun U](https://github.com/Arjun2099)
- [@Sidharth S Kumar](https://github.com/Sidharthssk)
- [@Avadhuta Sai Varun](https://github.com/saivarun4002)
- [@Karan-Rajesh-Nair](https://github.com/Karan-Rajesh-Nair)


## Project Link
 Automatic Pump and Water Level Controller
 - https://www.tinkercad.com/things/bayLkrNtSws-automatic-pump-and-water-level/editel
 
 
 ## Image

![SS](https://github.com/Karan-Rajesh-Nair/Automatic-Pump-and-Water-Level-Controller/blob/main/Image1.jpg)



<img width="654" alt="Screenshot 2022-10-21 at 4 48 48 PM" src="https://user-images.githubusercontent.com/91950083/197184179-32034522-539f-4829-832a-03721c5efab0.png">

as we can see green pointer it will indicate the height of the water level in the water tank , by providing the respective percentage by our screen, if water level is close then our led light will glow off and servo motor stops, this prevents overflow of water and helps in save much water



## Reference 
1.	Arduino Lessons by Paul McWhorter  
https://www.youtube.com/watch?v=d8_xXNcGYgo&list=PLGs0VKk2DiYx6CMdOQR_hmJ2NbB4mZQn-

2.	Arduino-based automatic water level indicator and controller project we are going to estimate the water level using ultrasonic sensors 
https://maker.pro/arduino/projects/automatic-water-level-indicator-and-controller-using-arduino-1

3.	Water Level Monitoring
https://create.arduino.cc/projecthub/Ramesh_Dofbot/water-level-monitoring-33aa4c
