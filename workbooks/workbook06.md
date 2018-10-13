# Workbook 6

## Section A -  EV3 start-up

Open the EV3 Mindstorms application

The EV3 application icon looks like this:

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/desktopIcon.PNG)

We would like to open a “New Program”, so that we can start working with our robot.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/newProgram.PNG)

1. In the “Lobby” (default screen), on the left, select “New Project”
2. Then select “New Program” and open.

This is the programming window, this is where we will be doing all of our programming.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/labelledCanvas.png)

## Section B - Distance sensing

It would be nice to let your robot roam free, but there is a good chance it will drive into things.

Since our robots don't have eyes, we will be using Lego's ultrasonic sensor. If your robot does not have the ultrasonic sensor already attached, do that now before continuing.

### Ultrasonic Sensor

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/sensorUltrasonic1.jpg "Ultrasonic Sensor")

The ultrasonic sensor can sense object up to 255cm away. If you look in the brick information area, you should be able to see the distance that the sensor is currently reading.

`Test with your robot. What is the furtherest that you could sense?`

`What was the closest?`

There are a number of different blocks that can make use of the Ultrasonic Sensor.

#### Loop

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/ultrasonicLoop.PNG "Loop based on Ultrasonic Sensor")

The block above loops around while the distance measured by the sensor is less than (<) 50cm.

#### Switch

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/ultrasonicSwitch.PNG "Switch based on Ultrasonic Sensor")

The block above switches between different blocks. It will run the block at the top if the distance measured by the sensor is less than (<) 50cm, and otherwise it will run the block at the bottom.

**NOTE:** The switch bock does not repeat on its own. As it is in the picture above, the switch will only run once. For it to run multiple time, the switch block must be placed within a loop (this can be a forever/infinite loop).

## Section C - Having some fun with the sensor

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/ultrasonicSound.PNG "Playing tones based on the sensed distance")

Have a look at the program above and see what it does. Just like a park distance sensor on a car, this program plays a ton to let you know how far you are from an object.

In the program, the value being read by the sensor is multiplied by 50, to make a tone that is high enough for us to hear. You can play around with this to find the best settings.

As the program is currently, the pitch of the tone gets higher, the further the distance.

`Could you modify the program to make the pitch go up as the robot gets closer to objects?`

`How would you do this?`

## Section D - Avoiding obstacles

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/avoid2.PNG "Avoid obstacles")

Program the blocks shown above.

This example allows the robot to freely drive about. The program has 2 switches in it. The inner-most switch lets the robot drive at 50% power if it is more than 20cm from an obstacle, but slows it to 10% if it is less than 20cm. The outer switch check if the robot is less that 10cm, and makes the robot reverse away from the obstacle, before turning to the right and continuing.

Give this a try.

`Did your robot drive into anything? If yes, explain why you think this happened.`

Try changing the block in this program to improve your robots abilities. Currently the robot can only make 90 degree turns to the right. Maybe see if you can make smaller or larger turns.

`Did this help? What did you try?`

### ROADBLOCK
#### This is only if you made it through all the other tasks before the end of the lesson

Having a robot that only turn right is no fun, and makes for some pretty boring exploration.

Add some blocks to your program to make your robots movements a bit more interesting.

`How have you made it more interesting?`

What would be great is if your robot could be more random. Sometimes turn left, sometimes right. Sometime do forward 3 rotations, sometimes 10. Try make it more random.

`How did you manage to make your robot more random?`

