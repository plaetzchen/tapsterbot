Building Instructions
=====

Robot
---

***Before building the robot you should connect the electronics once and run dance(); to make sure everything is working***

<h3>Base</h3>
Take the base plate and fix three 5x1 beams to the base plate using M5 20mm/10-32 3/4 inch screws and normal nuts. Connect the side panels to those beams using the same combination of screws and nuts.

<h3>Top and Arm</h3>



Electronics
----

<h3>Preperations</h3>

Take your Arduino and your Arduino ProtoShield out of their boxes and stack the ProtoShield on the Arduino (Don't push to hard!). Take the mini breadboard and stack it on the ProtoShield.

<h3>Connecting the Servos</h3>

Insert a row of three male headers into the Servo's conenctor and connect the servos to the breadboard. See this plan on how to connect the everything with jumper cables:

![Connection plan](instruction_imgs/connectingplan.jpg)

Installing Firmware
----
Connect your Arduino to your PC and run the Arduino Software (Download it at [arduino.cc](http://arduino.cc/en/Main/Software#toc2)). Select File -> Examples -> Firmdata -> StandardFirmdata and click the "Upload" button in the newly opened window.

After installing the StandardFirmware you can run the bot.js file from src directory with `node bot.js`. See [README.md](README.md) for further instructions