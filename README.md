# Traffic Rule Violation Detection System
## Abstract:
The increase in the number of vehicles in today’s time is serving a reason for the increase in traffic rule violations and various crimes associated with it. The traffic rule violation leads to various road accidents. 
The goal of the project is to automate the traffic rules violation detection system and make it easy to monitor the traffic and take action against the violated vehicle owner in a fast and efficient way. Detecting and tracking the vehicle and their activities accurately is the main priority of the system.
We plan to build software that can detect a car whenever it crosses a Red Light or overspeeds. We plan to use TensorFlow with an ssd object detection model to detect cars and from the detections in each frame, each vehicle can be tracked across a video and can be checked if it crossed the redlight and speed of that vehicle can be calculated. The vehicles that violate the speed limit are detected and notified using this. The license plate of the vehicle is also detected for identification purposes.
 		
## Inputs:
CCTV footage of the road in .avi format.

## Outputs:
The output of the software will consist of-Vehicle speed detected license plate photo of the vehicle extracted license plate number  

## Performance measurement criteria (Milestones and dates):
High accuracy of detecting all the vehicles even in high traffic conditions, detecting the license plate and extracting the license plate number would be the primary concern of this project. 

## Getting Started

The project is made by using tensorflow so you must be familiar with tensorflow and basic object detection and you must also know basic maths for understanding the tracking algorithm. You must be also familiar with linux OS as I have made this on Ubuntu and didn't test on other platforms.

### Prerequisites

Python packages to be installed

```
* Tensorflow (Tensorflow-gpu if you have Nvidia GPU)
* openCV
* imutils
* Pillow
* numpy
* tkinter
* urllib
* openALPR api
```
Make account on openalpr and get api secret key from [OpenALPR](https://www.openalpr.com/)

## Installing

Clone the repo and paste your secret key in [VehicleMoniter.py](https://github.com/ShreyAmbesh/Traffic-Rule-Violation-Detection-System/blob/master/VehicleMoniter.py) file on line 58.
run the project by the command ```python3 VehicleMoniter.py```


## Working Preview

![alt text](https://github.com/ShreyAmbesh/Traffic-Rule-Violation-Detection-System/blob/master/Screenshot1.png)

![alt text](https://github.com/ShreyAmbesh/Traffic-Rule-Violation-Detection-System/blob/master/Screenshot2.png)

##### Note
Do not run the file in the object detection folder cloned from tensorflow as I have made some changes to the files.

### Issues
If you find any problem you can contact me or raise an issue.

## Built With

* [Tensorflow](https://www.tensorflow.org/) - ML library
* [OpenALPR](https://www.openalpr.com/) - For detecting license plate and extracting license plate number

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/ShreyAmbesh/Traffic-Rule-Violation-Detection-System/blob/master/LICENSE) file for details
