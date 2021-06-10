# How-to-Make-Mini-Radar-Arduino-Based

Hello friends in this video I have made a Mini compact Radar with display, for that I have used HC-SR04 ultrasonic sensor, this sensor emit ultrasonic sound which came back to sensor after reflecting from an object,

all the data visualization is displayed on 1.8" ST7735 display, if any object detect by radar it'll show in display in red line.

For this project I have develop a custom made PCB and get it manufactured from JLCPCB.com

JLCPCB is one of the top leader in PCB manufacturing.

## VIDEO ##
https://youtu.be/60Vaq52BPk8

This is the complete  video of the proect you can watch here How I
build this cool gadget at homme and hw nicely it works

## COMPONENTS ##
There is four main components of this project

Arduino nano is the braing of our project

HC-SR04 is ultrasonic sensor this sensor emit ultrasonic sound waves which human can't listen , 

this sensor generate some value in proportion to the reflected ultrasonic sound waves from the object, 

on this we can also tell the distance of object from the sensor.

SG90 micro servo is used to rotate ultrasonic sensor in 180 deg

ST77535 display is our monitor to visualize all data on screen

Arduino nano :- https://amzn.to/2Eq3tSK

HC-SR04 ultrasonic sensor :- https://amzn.to/2SEU4vQ

SG 90 Servo :- https://amzn.to/2NG807N

1.8" ST7735 Dispaly :- https://www.instructables.com/How-to-Make-Mini-Radar-Arduino-Based/


## CIRCUIT DRAWING ##

Here is the link of circuit drawwing 
https://content.instructables.com/ORIG/FDT/X96D/JSSTYAQZ/FDTX96DJSSTYAQZ.png?auto=webp&frame=1&width=1024&height=1024&fit=bounds&md=7107f273adbd4e85cf5bdda9002862e9


## 3D FILES ## 


Complete 3D files will be available at thingiverse
https://www.thingiverse.com/thing:3465440

I have a Tevo Tarantula printer i have printed all parts on dark green PLA at 50 % infill

After printing all the parts or you can design your own model

if you don't have access to a 3D printer then you can use material like acrylic sheet or cardboard sheet.


## ARDUINO LIBRARY ##

Install this library in arduino IDE before compiling
https://github.com/olikraus/ucglib
