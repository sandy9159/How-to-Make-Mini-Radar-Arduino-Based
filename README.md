# How-to-Make-Mini-Radar-Arduino-Based

![a](https://user-images.githubusercontent.com/19898602/122661755-78216780-d1ab-11eb-8562-667fdfb241b0.JPG)


Hello friends in this video I have made a Mini compact Radar with display, for that I have used HC-SR04 ultrasonic sensor, this sensor emit ultrasonic sound which came back to sensor after reflecting from an object,

and this reflecting signals are processed  by Arduino and all the data visualization is displayed on 1.8" ST7735 display

if any object detect by radar it'll show in display in red line.

For this project I have develop a custom made PCB and get it manufactured from [JLCPCB.com](https://jlcpcb.com/IAT)

JLCPCB is one of the top leader in PCB manufacturing.

## VIDEO ##
https://youtu.be/60Vaq52BPk8

This is the complete  video of the proect you can watch here How I
build this cool gadget at homme and hw nicely it works

## COMPONENTS ##
There is four main components of this project

**ARDUINO NANO**  is the brain of our project

**HC-SR04** is ultrasonic sensor this sensor emit ultrasonic sound waves which human can't listen , 

            this sensor generate some value in proportion to the reflected ultrasonic sound waves from the object, 

            on this we can also tell the distance of object from the sensor.

**SG90 SERVO MOTOR** is used to rotate ultrasonic sensor in 180 deg

**ST77535 DISPLAY**  is our monitor to visualize all data on screen

**Arduino nano** :- https://amzn.to/2Eq3tSK

**HC-SR04 ultrasonic sensor** :- https://amzn.to/2SEU4vQ

**SG 90 Servo** :- https://amzn.to/2NG807N

**1.8" ST7735 Dispaly** :- https://www.instructables.com/How-to-Make-Mini-Radar-Arduino-Based/


## CIRCUIT DRAWING ##


![FDTX96DJSSTYAQZ](https://user-images.githubusercontent.com/19898602/122661962-1e21a180-d1ad-11eb-8eb7-6e8b9cf5540d.png)



## 3D FILES ## 

![FKU7HVEJSSTYATO](https://user-images.githubusercontent.com/19898602/122661995-427d7e00-d1ad-11eb-899d-0337d7053667.png)

Complete 3D files will be available at thingiverse
https://www.thingiverse.com/thing:3465440

I have a Tevo Tarantula printer i have printed all parts on dark green PLA at 50 % infill

After printing all the parts or you can design your own model

if you don't have access to a 3D printer then you can use material like acrylic sheet or cardboard sheet.


## ARDUINO LIBRARY ##

Install this library in arduino IDE before compiling
https://github.com/olikraus/ucglib

## CUSTOM MADE PCB ##
First of all here is the link of schematic of this project https://easyeda.com/editor#id=83c4ed4101c84bb68950179a24ab4322

PCB is the heart of this project, I have design like all the components must be surface mount on PCB so there is a big challenge is in front of me how to manage to buy different different components on my own. it quite difficult to get them all in time. so i came to know about PCB + SMT service of JLCPCB.COM like JLCPCB offering complete PCB with components solder on it. they have huge collection of components to choose from. this was so much help full for me it save my lots of time and money by using PCB + SMT service of https://jlcpcb.com/IAT and now there is also one good news for you you can now earn 10$ coupon for from JLCPCB just use https://easyeda.com/editor to design your PCB and order it from https://jlcpcb.com/IAT Design & Order on EasyEDA, PCB+SMT $10 Off: https://easyeda.com/editor Get $10 coupon & Join JLC&EDA Group: https://jlcpcb.com/EDA https://www.youtube.com/watch?v=rUtlYrG-U5g Watch full video https://www.youtube.com/watch?v=R9FUyvKBm8k


