# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

1.open the roboanalyzer software.

2.select the robot and its degrees of freedom.

3.change the values of X and Y wherever necessary.

4.simulate the model for inverse kinematics.

5.plot the graph between the joints.

6.update the DH parameters of the link configuration and end effector configuration.









### SIMULATION 
 
 RPR ROBOT:
 
 ![241127042-a1d85da0-b3dc-42b1-932e-bda3c6495de4](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/95135573-9ba6-4361-83a8-200003cbd6cb)

 ![241127103-12f311d2-4e92-4564-8dc3-d90a2fbaa66d](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/c9e9ecf6-9100-494f-8124-d999b3e022e0)

 3R ROBOT:
 ![241127183-64ac47b2-4d26-4bc9-88c1-3b6ec1e1cb1c](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/e1f4f65f-f99c-4502-b945-51941811fe45)

 
 
 ### PLOT 
 
 RPR ROBOT:
 
 
 
 ![241127281-13714435-af77-41ac-91a4-cec4580304ce](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/23b894ad-d4d5-41b1-bae0-ea383d761e6a)

 
 
 
 ![241127295-e3acfd10-3329-443f-8aa9-d6b09a4d0949](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/1b861147-b82f-4744-84c9-62488e4d9364)

 
 3R ROBOT:

 
 ![241127394-686c31a9-417e-4826-ad80-34b68b356231](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/9c577c66-5e44-47e4-b984-4c4af15bf451)



![241127412-d485f038-4303-4d85-821f-a63c8ddec2e2](https://github.com/Akashbalakrishnan/Inverse-kinematic-modeling-using-robo-analyzer-/assets/119291768/a5c42b3e-4808-4657-aca9-e97a7c6bcc4f)












### RESULTS :  

 Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.



