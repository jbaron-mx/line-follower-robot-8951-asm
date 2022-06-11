<p align="center">
  <img src="https://user-images.githubusercontent.com/11150471/173190042-5062206c-4337-4f95-a36e-23c459789584.gif" width="280">
</p>

<h4 align="center">A line follower robot programmed in assembly for the <a href="https://www.keil.com/dd/chip/2976.htm" target="_blank">microcontroller AT89C51</a>.</h4>

---

> This project was finished and presented in 2012 as part of a school project for the robotics program, this was the only robot among other participants that could finish the entire path on the first try.

> ASM code is shared as is with no alterations made since the competition in 2012, hence, there is room for optimizations and clean-up.

## Robot specifications
- The robot must follow a path that could have bifurcations along the way and the robot will have to decide which path to take according to the color and position of side-marks placed on the surface.
- The robot must be autonomous and not have any wired connection or remote control operated by humans or computers, the only wired connection accepted is the power cord for the robot.
- The robot dimensions must not exceed (25 x 20 x 20) centimeters.
- The robot must be prepared to function under varying light conditions, the participant cannot request any special light accommodations.

## Challenge specifications
- The path to follow will be a black line of 1.8cm wide over a white surface.
- The path can have bifurcations and before each, there will be a side-mark that determines which path the robot should follow.
- The side-marks consist of a black line and a gray line approximately 5cm before the bifurcation and of 5cm long each, positioned to the side of the main line and 2cm away from it.
- The main line and bifurcations could have 90º turns.
- The robot must stop when it detects the end of the path.

<img width="400" alt="example-line-path" src="https://user-images.githubusercontent.com/11150471/173192061-da09541b-668e-4de4-9375-a3e3f86a3074.png">

> Figure above is presented as an example, participants should not assume the final path will be identical.

## Material
- Microcontroller AT89C51.
- Double gear box.
- An array of 4x IR sensors for detecting the main path.
- Two IR sensors placed on the sides for detecting side-marks and color.
- 4x indicator leds.
