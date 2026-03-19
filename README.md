# Lab-Ex.-No---5-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
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

### output
![Screenshot 2025-05-19 100200](https://github.com/user-attachments/assets/f8531d26-9513-4d66-a263-5ff2d6977c57)

![Screenshot 2025-05-19 100210](https://github.com/user-attachments/assets/5d17a1f7-77bc-4e82-a2d5-e207fbf48bd4)

![Screenshot 2025-05-19 100226](https://github.com/user-attachments/assets/c8502d09-e0ac-4b89-b98c-764b224ca66a)

![Screenshot 2025-05-19 100236](https://github.com/user-attachments/assets/cc548dfd-d9fa-4135-aec0-7ae3e408a6ed)

![Screenshot 2025-05-19 100254](https://github.com/user-attachments/assets/0dd5c0a7-5817-4fc9-8ce1-2c6ed7bd996c)

![image](https://github.com/user-attachments/assets/f548ac71-3000-4d51-ac69-8fbb61b4638e)

![image](https://github.com/user-attachments/assets/dde40035-652b-4888-923c-b7c1f4916e12)

### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.
