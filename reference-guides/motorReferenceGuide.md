# Lego Motors

The Lego EV3 Mindstorms kit has two types of motors:
## Medium Motors
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/motorMedium1.jpg "Medium Motor")

## Large Motors
![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/hardware_images/motorLarge1.jpg "Large Motor")

# Motor Movement blocks

The Lego Mindstorms programming application provides 3 programming blocks for using the large motors.

**NOTE:** Because these are smart motors (discussed later), the motors is able to tell by how much is has turned. This means that when you turn by degrees, if something interferes or stops the motor completing the given degrees, then the program will hang, waiting to the motor rotation to complete.

## Large Motor

This block is used to turn a large motor.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockLargeMotor.PNG)

## Move Tank

This block is used when you would like to use both motors at the same time. The block allows you to individually adjust the speeds of each motor.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockMoveTank.png)

## Steer Tank

This block allows you to move the tank in a chosen direction.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/software_images/blockSteerTankDegrees360.PNG)

All of the programming blocks for motors allow you to work in seconds, degrees or rotations.

# Motor Positioning Blocks

These smart motors include encoders that can be used to identify the current rotational position of the motor.

This can be used to provide precise control over the motor movements.