# Lego Sensors

The Lego EV3 Mindstorms kit has many types of sensors:

## Colour Sensor
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/sensorColour1.jpg "Colour Sensor")

**NOTE:** The colour sensor tried to identify the colour what is reflecting the light, but is calibrated based on the *colours* used for Lego pieces. This means that certain colours might not be correctly identified.

### Example - Colour Speak

This example reads the information coming form the colour sensor and then used the speaker to say which colour is being detected.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/colourSpeak.PNG)

## Push Sensor
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/sensorPush1.jpg "Push Sensor")

## Rotation Sensor
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/sensorRotation1.jpg "Rotation Sensor")

## Ultrasonic Sensor
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/sensorUltrasonic1.jpg "Ultrasonic Sensor")

The ultrasonic sensor works up to 255cm.

**NOTE:** You can use the ultrasonic sensor in a "listen only" mode, which will make the sensor to only receive. This allows us to use the sensor to survey for robots also using the ultrasonic sensor.

### Example - Object Avoid

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/avoid2.PNG "Avoid obstacles")

This example allows the robot to freely drive about. The program has 2 switches in it. The inner-most switch lets the robot drive at 50% power if it is more than 20cm from an obstacle, but slows it to 10% if it is less than 20cm. The outer switch check if the robot is less that 10cm, and makes the robot reverse away from the obstacle, before turning to the right and continuing.