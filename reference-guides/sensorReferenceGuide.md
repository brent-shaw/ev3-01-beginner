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

### Example - Abject Avoid

This example allows the robot to freely drive about. When the robot is less that 100mm from an object, it will turn away, avoiding the object.