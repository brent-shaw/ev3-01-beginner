# Workbook 5

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

## Section B - Switches

Previously we learned about loops: a way to do something over and over.

As great as it is to endlessly do something, it would be nice if we could make changes, or check things in the middle of a loop.

This is where *switch* blocks come in. They allow for something to be checked, and based on this, different actions can be taken.

Lets look at an example.

### Identifying colours

Our robots can be equipped with a colour sensor. The colour sensor works by looking at the colour of light reflected off a surface.

Let's write a small program to play with the sensor using a switch and loop.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/colourSpeak.PNG)

This program uses an *infinite* loop, so that it will just continue to repeat what is in the loop over and over.

Every time it repeats, it uses a switch block to look at the colour being read by the colour sensor. If the colour is black, it uses the blound block to say so. The same goes for white.

Try out the program and see if you can get it to say black or white.

`How well does this work?`

Try extending your program so that it can identify other colour too.

It is not much of a robot if it doesn't move. Add some blocks to the program to try get your bot to drive around and identify colours.

`How did you do this?`

### Following a line

A standard program that many engineers and scientists implement when building robots is called *Line Following*.

This is exactly what it sounds like. You are trying to get your robot to follow a line.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/external/lineFollow.PNG)

The picture above gives an idea of how this is done. When the colour sensor sees one colour (the line), it must turn to one side, and when it sees the other it must turn the other way. Remember back to an earlier class when we tried to go forward using one motor at a time.

Here is a small program to get you started.

![alt text](https://raw.githubusercontent.com/brent-shaw/ev3-01-beginner/master/resources/program_images/lineFollow1.PNG)

`How well does this work?`

`What happens if you start on the wrong side of the line? And why does this happen?`
