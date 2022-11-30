# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

### Program:
![image](https://user-images.githubusercontent.com/94883079/204584824-5ad42834-55c1-42dd-9765-76c858d1590d.png)
![image](https://user-images.githubusercontent.com/94883079/204583615-e3101d8b-0ce2-4cee-bf53-d6fb3d6a3e7e.png)
![image](https://user-images.githubusercontent.com/94883079/204583999-7aff18b9-0605-43ce-996b-4f81d5381f3e.png)
![image](https://user-images.githubusercontent.com/94883079/204581629-5334e98a-d556-43b0-b2ce-1f85a3f0c680.png)
![image](https://user-images.githubusercontent.com/94883079/204581656-e0cc90e4-573e-401d-a354-e92834aacc5f.png)

### Linear Interpolation
![image](https://user-images.githubusercontent.com/94883079/204581832-18ec34f7-2a69-4f11-8cc0-596a413a790d.png)

### Circular Interpolation
![image](https://user-images.githubusercontent.com/94883079/204582462-2bb19b2b-1b3e-4014-b9af-17e7c4650e90.png)

### output

### Linear Interpolation:
![image](https://user-images.githubusercontent.com/94883079/204582661-d88fafba-fb30-418a-8816-6528fd37c012.png)

### Circular Interpolation:
![image](https://user-images.githubusercontent.com/94883079/204582732-e90e9c21-4701-4086-8ffb-283539cf7ebe.png)

### Result:
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
