# Workbook 4

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

## Section B - Loops

Sometimes when writing a program, you end up with long chains of blocks that all to the same, or very similar things.

To avoid copying and pasting the same block over and over, we can instead use a loop block to repeat that action a number of times.

### Driving in a square

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/square.PNG)

This is what a program to make your robot move in a square would look like. If you haven't yet made your robot do this, take the time now to make this program.

A square is not a very complicated shape, but as you can see, the program is already getting quite large.

If you look at the blocks though, you can see that there is a pattern:
* Go forward
* Turn right
* Repeat

This is where loops comes in. Loops allow you to specify a set of instructions (blocks), and then they let you repeat those instead of copying and pasting them over and over.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/square(loop).PNG)

This is a much simpler looking program. As you can see, there is a move tank block and a steer tank block inside of a loop block. The loop block is then set to 'Count' up to 4 (because squares have 4 sides).

`Did your robot move in a square?`

`How would you modify the program to make your robot drive in a larger square?`

### Exploring loops

Loops work repeating until a certain condition is met. This could be counting up to a number, running until something happens, or running forever.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/loopTest.PNG)

The program above shows how the counting loop can be used to provide a number that can be used control something. 

Copy this program above and look at how it works.

`What does this program do?`

## Lesson challenge

Previously your robot drive in a square. Let's try some more complicated shapes.

`Can you make your robot do a triangle, hexagon or star?`

`Which shape did you do?`

`How did you do this?`

### ROADBLOCK
#### This is only if you made it through all the other tasks before the end of the lesson

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Chessboard480.svg/176px-Chessboard480.svg.png)

This is a chess board. It is an 8 by 8 grid (64 squares). The challenge for this roadblock is to program your robot to drive so that it goes over every block on the baord.

To to use loops to do this.

`How did you do this?`