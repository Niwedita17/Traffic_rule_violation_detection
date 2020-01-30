# Traffic Rule Violation Detection System
## Abstract:
The increase in the number of vehicles in today’s time is serving a reason for the increase in traffic rule violations and various crimes associated with it. The traffic rule violation leads to various road accidents. 
The goal of the project is to automate the traffic rules violation detection system and make it easy to monitor the traffic and take action against the violated vehicle owner in a fast and efficient way. Detecting and tracking the vehicle and their activities accurately is the main priority of the system.
We plan to build software that can detect a car whenever it crosses a Red Light or overspeeds. We plan to use TensorFlow with an ssd object detection model to detect cars and from the detections in each frame, each vehicle can be tracked across a video and can be checked if it crossed the redlight and speed of that vehicle can be calculated. The vehicles that violate the speed limit are detected and notified using this. The license plate of the vehicle is also detected for identification purposes.
 		


## Inputs:
CCTV footage of the road in .avi format.

## Outputs:
The output of the software will consist of-
Vehicle speed 
detected license plate photo of the vehicle
extracted license plate number  

## Performance measurement criteria (Milestones and dates):
High accuracy of detecting all the vehicles even in high traffic conditions, detecting the license plate and extracting the license plate number would be the primary concern of this project. 
