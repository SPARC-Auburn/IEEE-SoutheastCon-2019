# IEEE Southeastcon Hardware Competition 2019 Team - Auburn University
## Overview
The purpose of this project is to create a robot to compete in the 2019 IEEE SoutheastCon held in Huntsville, AL.  The conference is centered around sharing and demonstrating technical advancements in engineering.  We competed in the hardware competition against 40 other universities from across the southeastern US.  This project was a collaboration between Auburn's [Student Project and Research Committee (SPARC)](http://sparc.eng.auburn.edu/) and an electrical engineering senior design team.

## Game Overview
The function of the robot is to move around a square carpeted area with a side length of 244 centimeters, and pick up small objects on the field and place them into one of four colored home bases based on the color of the object. The arena is split into two zones.  Zone one features four home bases corresponding to four different colors. The robot starts in one of the four home bases.  Zone two is separated by a one-inch thick white line.  Zone two is where twelve objects are placed for the robot to pick up: eight two inch wooden cubes, and four 2.5 inch diameter pit balls. The arena features a wooden box in the middle that serves as an obstacle as well as four LED lights situated at the edge of zone two on the one-inch line.  The four home bases are placed at the four corners of the arena in zone one.  An arena was built in order to test the robot as shown in Figure 0.  This allows testing of the robot in a controlled area leading up to the competition.

<img src="Images/Field%20Testing/field.JPG" width="400px"/>

**Figure 0:** Field Constructed in Broun Hall room 368 

The competition had some other ways to score points such as leaving the home base, going in circles (orbits) around the center structure, and raising a flag.  There is a penalty to colliding with the flashing lights (spacetels).  Table 1 displays a summary of the scoring methods.  

<img src="Images/Field%20Testing/scoring.png"  width="400px"/>

**Table 1:** Summary of scoring methods

## Robot Constraints
The robot has several constraints that limit the size of the robot, materials used in the construction that assure the safety of participants and other robots ([Competition Rules](http://sites.ieee.org/southeastcon2019/files/2019/02/2019-SoutheastCon-HW-Rules_v1_3-1.pdf)).  The robot’s width and length must be within a nine by nine-inch area and a max height of eleven inches.  The nine by nine area must include a bumper covering eighty percent of the perimeter.  The bumper must be 1.5 inches from the ground and have a minimum vertical cover of one inch, and must not have a radius of curvature less than one centimeter.  This is to prevent damage to the arena and other robots in the event of a collision.  The robot can also raise a mechanical arm, with a max length of three inches, with a flag presenting the competing school’s name.

## Our Approach
The robot utilizes two Raspberry Pi microcomputers to control the motors while using an attached camera to identify the color and shape of the objects on the field.  A LIDAR is used to localize the robot on the arena to help avoid the four lights and the wooden box in the middle of the arena.  The design of the robot is to move the objects to the appropriate home base by running over the objects, closing a small door on the front of the robot, hold them under the robot and move towards the appropriate home base of the object.  Figure 1 shows the final robot design.

<img src="Images/Mechanical%20Development/final-bot.jpg"  width="400px"/>

**Figure 1:** Final robot design


## Technical Documentation
* [Mechanical](https://github.com/SPARC-Auburn/IEEE-SoutheastCon-2019/tree/master/Mechanical-Hardware)
* [Electrical Hardware](https://github.com/SPARC-Auburn/IEEE-SoutheastCon-2019/tree/master/Electrical-Hardware)
* [Software](https://github.com/SPARC-Auburn/IEEE-SoutheastCon-2019-Software)

## Team Leadership
* **Team Lead:** Matthew Castleberry (@mcberry23): mtc0030@auburn.edu  
* **Electrical Lead:** Josh Jablonowski (@jdj0019): jdj0019@auburn.edu  
* **Mechanical Lead:** Alex Jones (@alextigernick): naj0016@auburn.edu
