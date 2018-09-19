# Workbook 2

## Section A -  EV3 startup

Open the EV3 Mindstorns application

The EV3 application icon looks like this:

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/desktopIcon.PNG)

We would like to open a “New Program”, so that we can start working with our robot.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/newProgram.PNG)

1. In the “Lobby” (default screen), on the left, select “New Project”
2. Then select “New Program” and open.

This is the programming window, this is where we will be doing all of our programming.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/labelledCanvas.png)

## Section B – Ports and the brick

When we refer to the Brick, we refer to the side with the keypad and screen as the Top.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/brickTop2.jpg "Top view of EV3 Brick")

If you look at your brick, you will see that there are two sets of ports.
On the Front of the brick, there are ports labelled with letters.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/brickFront1.jpg "Front view of EV3 Brick")

On the Back of the brick, are ports labelled with numbers. The ports labelled with numbers are used when adding sensors to your robot. We will be covering this in another class.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/brickRear1.jpg "Rear view of EV3 Brick")

Let's look at the ports labelled with letters. Your robot should currently have two of these ports used, with cables going to the two large motors in your robot.

Port B should be connected to the motor on the left of the robot, and Port C should be connected to the motor on the right.

## Section C – Lego Motors

The Lego EV3 Mindstorms kit has two types of motors:
### Medium Motors
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/motorMedium1.jpg "Medium Motor")

### Large Motors
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/motorLarge1.jpg "Large Motor")

## Section C – Motor Programming blocks

The Lego Mindstorms programming application provides 3 programming blocks for using the large motors.

**Large Motor** - This block is used to turn a large motor.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockLargeMotor.PNG)

**Move Tank** - This block is used when you would like to use both motors at the same time. The block allows you to individually adjust the speeds of each motor.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockMoveTank.png)

**Steer Tank** - This block allows you to move the tank in a chosen direction.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockSteerTankDegrees360.PNG)

All of the programming blocks for motors allow you to work in seconds, degrees or rotations. **NOTE:** Today we will be using degrees.

## Section C – Moving your Robot

Set your Robot up so that you can see the wheel. Rotate the wheel so that the indicator is in the upright position (12 o'clock).

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/robotWheelIndicator.JPG)

Add a Large Motor programming block to your programming canvas, and put the block in "On for degrees" mode, and run it for 360 degrees at a speed of 10.

`What did you see? `

Add another Large Motor programming block, and try to make your robot move forward.

`Could you do this? How?`

Now add a Move Tank block. Try move your tank forward.

`Was this easier?`

Using 2 Move Tank blocks and a Large Motor block, make you robot go forward, then turn around and come back. Make sure you have marked where the robot is starting from.

`How did you do this? Is the robot exactly where it started? `

Now use a Steer Tank block: Set the steering to 50, and the speed to 10. Make sure that the indicators on the wheels is in the upright position (12 o'clock).

`What happens when you run this block? `

Now set the steering to 100. Again, make sure that the indicator on the wheel is in the upright position (12 o'clock).

`What happened this time?`

Using 2 Move Tank blocks and a Steer Tank block, make you robot go farward, then turn around and come back.

`Was anything different this time?`

## Lesson challenge

Now try make your robot drive in a square. Use any blocks you like to do this.

`Was this difficult, or easy?`

`Explain how you did this:`

### ROADBLOCK
#### This is only if you made it through all the other tasks before the end of the lesson

Using any blocks you would like, try make your robot drive in a circle, ending exactly where it started. If you can do that, your try your hand at a figure of 8.

`Explain how you accomplished these. What was the most difficult part?`