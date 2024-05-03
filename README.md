# Metalcow Coding Conventions
This repository consists of all the coding conventions and practices that the code team should follow when working on a project. 

### Files in the project
&emsp;- **Main.java**  
&emsp;&emsp; 1. Contains code necessary for main robot aplication.  
&emsp;&emsp; 2. Users ***should not*** touch this class.  
  
&emsp;- **Robot.java**  
&emsp;&emsp; 1. Responsible for the main control flow of the robot code.  
&emsp;&emsp; 2. This is the class that is called when the robot is started and enabled.  
&emsp;&emsp; 3. All the subsystems are called here and joystick controls are defined.

&emsp;- **Constants.java**  
&emsp;&emsp; 1. Consists of all the global constants that need to be accessed by the subsystems.  
&emsp;&emsp; 2. Examples: Angles of the arm for each position, PID constants for swerve, Drivetrain speed, Autonomous speed etc.  

&emsp;- **SwerveModule.java**  
&emsp;&emsp; 1. Consists of the code to initialize each of the four swerve modules on the robot.  
&emsp;&emsp; 2. Includes the module number, the angle offset, and the encoders for each module.  
&emsp;&emsp; 3. Also includes a few methods that can access the position and rotation angle of the swerve module.  

&emsp;- **Subsystems Folder**  
&emsp;&emsp; 1. Consists of all the subsystem files that correspond to a subsystem on the robot.  
  
&emsp;- **Autos Folder**  
&emsp;&emsp; 1. Consists of all the autonomous commands that can be used in the autonomous period (Accesses the subsystems to make commands).  
&emsp;&emsp; 2. Used with Pathplanner to perform actions such as arm movement. 
