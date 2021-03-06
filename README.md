# Delta-Robot
This project consisted of the design and manufacturing of a 2-DOF parallel robot, as well as the integration of a cognex camera to detect the position of a part
in a conveyor and the control of 2 servomotors through the use of a S7 1200 PLC, with the objective of moving the part from conveyor A to conveyor B. <br> 

# What I did
1. My main contribution to the project was in the area of coding, which includes the following tasks. <br> 
 &nbsp;&nbsp;&nbsp;&nbsp; a) I was resposible for the TIA Portal implementation of inverse cinematic equations that allowed for the calculation of the necessary angles to reach any point within the robot's work area. <br> 
 &nbsp;&nbsp;&nbsp;&nbsp; b) I generated a set of functions through the use of Motion Control blocks that allowed the motors to rotate, starting from an angle of reference and positioning the arms for the end effector to reach the required coordinates. <br> 
 &nbsp;&nbsp;&nbsp;&nbsp; c) I coded an HMI that allowed the user to enable and disable the different oppperation modes of the robot, inlcuding free movement through an coordinate input, the execution of the routine to move the part between conveyors and a function to return the robot to home. <br> 
 &nbsp;&nbsp;&nbsp;&nbsp; d) I implemented the commands in InSight Explorer to detect the part on the conveyor and determine its position in terms of the reference system of our robot. I also stablished the PROFINET connection between InSight Explorer and TIA Portal for the position data to be transmited from the camera to the PLC. <br><br>  
2. I was in charge of the geometric synthesis, stablishing dimensions for each element of the robot in order for it to be able to cover a 45x20 cm work area. <br> <br> 
3. I colaborated with my teammates to model all the necessary parts to build the robot through the use of CAD, ensuring an efficent use of materials, as well as a proper fit between the parts for a seamless mechanical performance. <br> <br> 
4. I also colaborated in the manufacturing of the parts, through multiple techniques, that included both convencional and CNC milling machine, lathe, and finishing equipment, such as the band saw and the emery. <br> 
