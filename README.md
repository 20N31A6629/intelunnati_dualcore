# intelunnati_dualcore
 ROAD OBJECT DETECTION WITH DEEP LEARNING

									Author:
								K. Sai Bhuvaneswari 
								T. Mounika  
								19/July/2023.

**Abstract:**
This project focuses on road object detection using deep learning techniques, specifically targeting the detection of various objects such as persons, vehicles, and birds also counts them. Accurate detection of objects on roads is crucial for applications like autonomous driving, traffic monitoring, and surveillance systems. 
Traditional computer vision methods often struggle with the challenges posed by complex backgrounds, occlusions, and variations in lighting conditions. Deep learning approaches, particularly convolutional neural networks (CNNs), have shown significant advancements in improving the accuracy and robustness of road object detection.
The project involves the exploration and implementation of state-of-the-art deep learning architectures, including OpenCV, YOLO (You Only Look Once). 
Special attention is given to the challenges encountered in road object detection, such as the detection of small objects, handling occlusions, and meeting real-time processing requirements. To address these challenges, aiming to improve detection performance in complex scenarios.
Experimental results demonstrate the effectiveness of the deep learning-based road object detection system in accurately detecting persons, vehicles, birds, and other specified objects on roads. 

**MODEL Used:**
**YOYO3** 
YOLO stands for You Only Look Once. It is a real-time object recognition algorithm. It can classify and localize multiple objects in a single frame. YOLO is a very fast and accurate algorithm for its simpler network architecture.

**Introduction:**
In this project, we’ll detect and classify cars, HMV ( Heavy Motor Vehicle) , LMV (Light Motor Vehicle) on the road, and count the number of vehicles traveling through a road. And the data will be stored to analyse different vehicles that travel through the road.
We’ll create two programs to do this project. The first one will be the tracker for vehicle detection using OpenCV that keeps track of each and every detected vehicle on the road and the 2nd one will be the main detection program.
 

**Prior Work**
1. Python – 3.x (We used python 3.8.8 in this project)
2. OpenCV – 4.4.0
3. NumPy – 1.20.3
4. YOLOv3 Pre-trained model weights and Config Files.
**Approach:**
1.	Import necessary packages and initialize the network.
2.	Read frames from a video file.
3.	Preprocess the frame and run the detection.
4.	Post-process the output data.
5.	Track and count all vehicles on the road.
6.	Save the final data to a CSV file.

**Result:**
The trained deep learning models demonstrate excellent performance in detecting persons, vehicles, birds, and other specified objects on the road. The models achieve state-of-the-art results on benchmark datasets, exhibiting high precision and recall rates across the selected object categories.

 **Reference:**
https://github.com/alen-smajic/Real-time-Object-Detection-for-Autonomous-Driving-using-Deep-Learning

**Conclusion:**
In this project, we’ve built an advanced road object detection and classification system using OpenCV. We’ve used the YOLOv3 algorithm along with OpenCV to detect and classify objects. And we learned about deep neural networks, file handling systems, and some advanced computer vision techniques. The accurate detection ,classification and counting of vehicles ,people ,birds would give useful insights like where the traffic is heavy, which kind of vehicles travel more in a particular route ,etc. The system works as an automated video analytical tool for real time vehicle detection.  Since this task is very difficult manually, the automation would save a lot of time and effort. It will be helpful in various applications such as Traffic management, Safety , Environmental monitoring.



