# Device-lab4

# Paper Puppets

*A lab report by Ankit M.*

## Part A. Actuating DC motors

**Link to a video of your virbation motor**

## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**

Red connects to Power (5V)
Brown connects to Ground (GND - 0V)
Orange connects to Pin 9 (signal pin)

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

Pin 9 or 10 is ideally mentioned in the servo description

**b. What aspects of the Servo code control angle or speed?**

The pos function controls the angle (0/90/180 and so on). The speed of the motion is the same as the loop cycles. Delay controls the speed. Reducing Delay makes the loop run faster, and thus the servo runs faster

## Part C. Integrating input and output

**Include a photo/movie of your raw circuit in action.**

In the current setup, the servo is running at a delay of 5ms and the angle is 0->90->0. (shorter angle cycle and higher speed). The video and image are included below,

[Video of the setup](https://i.imgur.com/RHjNDzy.mp4)
<br>
[Image of the Circuit]<br><img src="https://i.imgur.com/rzWfJDL.jpg" height="50%" width="50%"><br>

## Part D. Paper puppet

**a. Make a video of your proto puppet.**

## Part E. Make it your own

**a. Make a video of your final design.**
