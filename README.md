# How-to-Make-Mini-Radar-Arduino-Based

![a](https://user-images.githubusercontent.com/19898602/122661755-78216780-d1ab-11eb-8562-667fdfb241b0.JPG)


Hello friends in this video I have made a Mini compact Radar with display, for that I have used HC-SR04 ultrasonic sensor, this sensor emit ultrasonic sound which came back to sensor after reflecting from an object,

and this reflecting signals are processed  by Arduino and all the data visualization is displayed on 1.8" ST7735 display

if any object detect by radar it'll show in display in red line.

For this project I have develop a custom made PCB and get it manufactured from [JLCPCB.com](https://jlcpcb.com/IAT)

JLCPCB is one of the top leader in PCB manufacturing.










## VIDEO ##

[![](https://img.youtube.com/vi/60Vaq52BPk8/0.jpg)](https://www.youtube.com/watch?v=60Vaq52BPk8)

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

## CUSTOM MADE PCB ##

![A3](https://user-images.githubusercontent.com/19898602/122663819-e1f53d80-d1ba-11eb-8929-472ee2f69472.JPG)
![A4](https://user-images.githubusercontent.com/19898602/122663820-e3266a80-d1ba-11eb-917f-5125248cf39f.JPG)
![A5](https://user-images.githubusercontent.com/19898602/122663821-e3bf0100-d1ba-11eb-9ab1-d2d3045d0caf.JPG)


I am using here a cutom made PCB using PCB for your project is very much important.
you will get good result, neat and clean wiring and professional look for your project.
I designe this two layer PCB and ordered it from [JLCPCB](https://jlcpcb.com/IAT)
I always prefer [JLCPCB](https://jlcpcb.com/IAT) because there PCB prices are very cheap
currently thay have Special offer: $2 for 1-4 Layer PCBs, free SMT assembly monthly
and If you register yourself today on [JLCPCB](https://jlcpcb.com/IAT) you will get $18 coupons exclusively 
So what are you waiting for just visit  [JLCPCB](https://jlcpcb.com/IAT)






## 3D FILES ## 

![FKU7HVEJSSTYATO](https://user-images.githubusercontent.com/19898602/122661995-427d7e00-d1ad-11eb-899d-0337d7053667.png)

Complete 3D files will be available at thingiverse
https://www.thingiverse.com/thing:3465440

I have a Tevo Tarantula printer i have printed all parts on dark green PLA at 50 % infill

After printing all the parts or you can design your own model

if you don't have access to a 3D printer then you can use material like acrylic sheet or cardboard sheet.


![A1](https://user-images.githubusercontent.com/19898602/122663228-7e691100-d1b6-11eb-9431-4af2924453d8.JPG)

First I have design the parts in CAD software, then I 3D printed those
Parts using PLA filament you can download all the 3D files links are given above.


![A2](https://user-images.githubusercontent.com/19898602/122663229-7f01a780-d1b6-11eb-8ced-51d81340f313.JPG)

Then I arrange all the required electronics components.
As you can see here, I used components like
Arduino nano
HC-SR04 Ultrasonic Sensor
Tower pro servo motor
1.8” ST7735 DISPLAY
9V Battery


![A5](https://user-images.githubusercontent.com/19898602/122663230-7f9a3e00-d1b6-11eb-9866-c270eea9bb17.JPG)

Then I soldered some header pins on PCB and placed components on to them

![A6](https://user-images.githubusercontent.com/19898602/122663231-7f9a3e00-d1b6-11eb-9cd9-8bbf99b04080.JPG)

This PCB placed inside the 3D printed box this is the base portion of our radar

![A7](https://user-images.githubusercontent.com/19898602/122663232-8032d480-d1b6-11eb-874b-43270f508f0f.JPG)

After placing all the components & battery inside the radar I placed the top cover 
to its place. The HC-SR4 sensor is connected with servo motor.


![A8](https://user-images.githubusercontent.com/19898602/122663227-7d37e400-d1b6-11eb-9274-eded28f92592.JPG)






## ARDUINO LIBRARY ##

You can download the arduino code attached above
Install this library in arduino IDE before compiling
https://github.com/olikraus/ucglib




