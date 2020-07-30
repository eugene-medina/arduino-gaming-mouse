# arduino-gaming-mouse
Arduino-based gaming pointer mouse using IMU

I have always wondered if the classical mouse can be modified for a more-engaging type of input to be used in fps-style games, as well as simulation-style games. In this project, the objective is to simulate mouse controls using an Arduino and an Inertial Measurement Unit module such as the MPU6050. 

A basic gaming mouse, or a typical (ordinary) mouse for that matter, has at least three buttons as inputs - left click, right click, middle button (wheel or otherwise). These three inputs will likewise be simulated. Android keyboards have been around for a while. These keyboards have built-in accelerometers to emulate mouse movements. My original idea is to hack an inexpensive Android keyboard, use the accelerometer for mouse movements, and use SPST switches in parallel with the keys on the keyboard. Crude but effective. However, with some experimentation, it turns out that the accellerometer used in the cheap Android keyboard I used is not up to the task. After all, it was designed to be a mouse pointer for general use, not for gaming.

I used an Arduino clone I got through Ebay from DIY More. I like their DM Pro Micro module, as it offered additional analog ports on their breakout board. I like this board because it has built-in 3V3 voltage regulator - very convenient for connecting to the IMU MPU6050, and the nRF24L01+ transceiver.


