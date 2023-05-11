# EX NO.2-Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
##### 1.open the roboanalyzer software.
##### 2.select the robot and its degrees of freedom.
##### 3.change the values with the link lenght wherever necessary.
##### 4.simulate the model for forward kinematics.
##### 5.plot the graph between the link and the joints.
##### 6.update the DH parameters of the link configuration and end effector configuration.




### SIMULATION 
 ## 6 DOF:
 ![6 DOF 1](https://github.com/IamShakthi/Forward-kinematics-using-robot-analyzer/assets/117913445/7d2df985-2ad2-4494-be74-4272537f9d4c)

 
 ## 4 DOF:
 ![4 DOF 1](https://github.com/IamShakthi/Forward-kinematics-using-robot-analyzer/assets/117913445/6edc6e24-c5e3-483e-a5ac-7e81df62424c)

 
 
 ### PLOT 
   ## 6 DOF:
 ![6 DOF 2](https://github.com/IamShakthi/Forward-kinematics-using-robot-analyzer/assets/117913445/7621be9a-4679-4dec-a77e-1d28e172ac34)

 
 ## 4 DOF: 
 ![4 DOF 2](https://github.com/IamShakthi/Forward-kinematics-using-robot-analyzer/assets/117913445/1eb94096-826b-4c5f-b69d-a79e9556227d)


 ![4 DOF 3](https://github.com/IamShakthi/Forward-kinematics-using-robot-analyzer/assets/117913445/0be0bf0e-ec15-41a6-9924-f2bf089f1bf3)

 
 
 
 
### RESULTS :  
 Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
