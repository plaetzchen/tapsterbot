Building Instructions
=====

Robot
---

***Before building the robot you should connect the electronics once and run dance(); to make sure everything is working. Also you should use a round file on 3D printed parts to make sure all holes are fitting.***

<h3>Base</h3>
[![Base](http://farm8.staticflickr.com/7303/9309912641_8a5bd269b2_m.jpg)](http://www.flickr.com/photos/99107062@N08/9309912641/in/set-72157634689374194)

Take the base plate and fix three 5x1 beams to the base plate using M5 20mm/10-32 3/4 inch screws and the low-profile nuts. Connect the side panels to those beams using the same combination of screws and nuts.

<h3>Actuator</h3>

***Make sure not the tighten the screws on the actuator. Each part should be moving without using a lot of power.***

[![Arm first step](http://farm8.staticflickr.com/7425/9309912429_673ca3b002_m.jpg)](http://www.flickr.com/photos/99107062@N08/9309912429/in/set-72157634689374194/)

Take two 2 17x1 plates and fix a 2x1 beam to each of it ends using the M5 20mm/10-32 3/4 inch screws and lock nuts. Repeat three times.

[![Connection arm to the ](http://farm8.staticflickr.com/7352/9312700452_fd14a33fb6_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312700452/in/set-72157634689374194/)

Connect two arms to each connector of the stylus holder. Use the M5 30mm/10-32 1 1/4 inch screws and lock nuts. Please note that the stylus holder has two sides, the smooth side should be visible (like on the picture) and the screws of the arms should face up.

[![Servo mount](instruction_imgs/servomount_small.jpg)](instruction_imgs/servomount.jpg)

Connect the upper arm to each of the three arms connected to the stylus holder. Use the M5 30mm/10-32 1 1/4 inch screws and lock nuts. Connect each servo to the upper arm using the screws that came with the servo. The servo should be parked in its zero point when doing this and you need to screw the 2-side horn on the servo (see the servo's instructions). Use the second hole on each side of the horn for the screws. (Please note that the screws on the end of the arm are upside-down.)

[![Connecting servo holders](http://farm3.staticflickr.com/2823/9312698006_08e27dc15e_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312698006/in/set-72157634689374194/)

Fix the servo mounts to the servos using a M3 18 mm / 6-32 3/4 inch screw and the equivalent nuts for each side. (Note that that the upper arm was exchanged for a 9x1 beam in the picture.)

<h3>Top</h3>

[![Top with servo mount points](http://farm6.staticflickr.com/5348/9312699394_d204fed47c_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312699394/in/set-72157634689374194/)

Connect three 9x1 beams to the top plate using the M5 20 mm / 10-32 3/4 screws and low-profile nuts. The screw head should be upper surface of the top plate.

[![Connected actuator](http://farm6.staticflickr.com/5340/9312695064_9e1f132294_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312695064/in/set-72157634689374194/)

Connect the servo mounts to the 9x1 beams using M5 25 mm / 10-32 1 inch screws and low-profile nuts. Run the servo cables in the hole of the top plate. Please make sure that the servo horns are all facing to the right side and each servo mount is mounted to the left side of the 9x1 beam.
Also note that the 17x1 plates are facing to the outside and the screws heads on the stylus mount  

If you connected it the right way the arm should be movable in each direction without any colliding screws or similar.

[![Preparing case for top](http://farm8.staticflickr.com/7424/9309907353_0555d70db5_m.jpg)](http://www.flickr.com/photos/99107062@N08/9309907353/in/set-72157634689374194/)

Connect a 5x1 beam to each of the side parts using M5 20 mm / 10-32 3/4 inch screws and low-profile nuts. 

[![top plate conneted to the casing](http://farm8.staticflickr.com/7436/9312694916_1eb2d1b904_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312694916/in/set-72157634689374194/)

Fix the top with the actuator to the rest of the casing using M5 20 mm / 10-32 3/4 inch screws and low-profile nuts.

<h3>Stylus</h3>

[![Stylus](http://farm3.staticflickr.com/2829/9315900080_f96e76ce30_m.jpg)](http://www.flickr.com/photos/99107062@N08/9315900080/)

Insert the stylus into the stylus mount. You may need to use tape on the stylus or a rasp to insure a tight fit.

<h3>Arduino mount</h3>

[![Arduino with Arduino plate](http://farm6.staticflickr.com/5546/9312694432_073b253282_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312694432/in/set-72157634689374194/)

Mount the Arduino to the Arduino plate using the A2 M2.5 12mm / 4-40 1/2 inch screws and nylon nuts. Make shure not to tighten the screws. The arduino should be fixed but the PCB should never bent!

[![The Arduino fixed to the top plate](http://farm4.staticflickr.com/3665/9312694218_57eeff4650_m.jpg)](http://www.flickr.com/photos/99107062@N08/9312694218/in/set-72157634689374194/)

Mount two 9x1 beams and the Arduino plate on the top using M5 25 mm / 10-32 1 inch screws and low-profile nuts.

Electronics
----

<h3>Preparations</h3>

Take the ProtoShield and and stack it on the Arduino (Don't press two hard!). Glue the mini breadboard on the ProtoShield using the glue pad that came with the breadboard.

<h3>Connecting the Servos</h3>

Insert a row of three male headers into the servo's connector and connect the servos to the breadboard. See this plan on how to connect everything with jumper cables:

![Connection plan](instruction_imgs/connectingplan.jpg)

Installing Firmware
----
Connect your Arduino to your PC or Mac and run the Arduino Software (Download it at [arduino.cc](http://arduino.cc/en/Main/Software#toc2)). Select File -> Examples -> Firmdata -> StandardFirmdata and click the "Upload" button in the newly opened window.

After installing the StandardFirmware you can run the bot.js file from src directory with `node bot.js`. See [README.md](README.md) for further instructions

<h4>Copyright notice</h4>
Most images in this document are made by Abby Raskin. All rights reserved.
The images from the upper arm are made by Philip Brechler. Free to use for anyone.