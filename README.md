# NGL-for-MPC-Documentation
A documentation for version control and details about NGL that implemented inside MPC Robot.

[Open the wiki for further Documentation](https://github.com/ReNubProgrammer/NGL-for-MPC-Documentation/wiki)

#How to Run
Please use the Main Program by access folder Main/Main Control.vi

# Hardware Requirement
Robot Requirement:
- MPC v2.0fa< => MPC v3
- MPC v3.0> => MPC v4
- MPC v4.0> => MPC v4.1

# Version Log

#MPC v4.2b
- Sanitation for custom sequential program
 
##MPC v4.2a
- Ultrasonic Function added on:
  - System Parameters
  - System Status
  - movesens
  - linefol
  - bal
- Update custom sequential program
- Adjustment Forklift (Calculation and System Parameters)
- Continues Servo for Magazine (Duty Max & Min)
- Customization on Servo Channels and Home Position
- Add Testing Function for Custom Sequential Program 

##MPC v2.0fa
- Add Slider in the forklift

##MPC v2.0f
- Add Table of Order Identifier and Learning VI
- Add Color Pattern Matching for Object Identifier and Learning VI
- Temporarily add program for gripper function

##MPC v2.0a
- Merging 1.0gb and 1.0gc
- Actuator, global var set param
- Line sensor, global var set param

# Bug Report
- Gripper equation is not applicable
- Color Matching can be improved by Pattern Matching
- PID in forklift need tuning properly
- Efficiency the vision program that affect the robot functions
