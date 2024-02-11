INTRODUCTION   
I. IMAGE PROCESSING
Image processing deals with the processing of 2D images such as making transformations, applying segmentation, contrast, smoothing etc. It enhances images and make it more easy to read and interpret. It’s a discipline in which both the input and output of a process are images [1].  

II. COMPUTER VISION
It is concerned with the theory and technology which build artificial systems that obtain information from images in order to produce some action [2].
III. DISTINCTION BETWEEN IMAGE PROCESSING AND COMPUTER VISION
Both the fields are interrelated. It is hard to distinguish where image processing stops and computer vision starts. But according to few authors both the fields have difference in their goals. Image Processing involves enhancement of images whereas aim of Computer Vision is to imitate human vision, including learning and make conclusion and take actions on the base of visual inputs [3]. However, emulating human vision may also require image enhancement so in most real cases computer vision relies on image processing [1]. 
This project is comprised of both the fields. It includes image processing techniques such as image enhancement and also involves computer vision to make the artificial intelligent system.
IV. INTRODUCTION OF TRAFFIC CONTROL SYSTEMS 
Traffic signal control systems play vital role in smooth routing of traffic. These Systems use signals to ensure the smooth and safe flow of traffic. Traffic signals are mounted on the roads junction and are used to give vehicular and pedestrian right off way [4]. They encourage the systematic movement of pedestrian and vehicular traffic and avert unnecessary wait to traffic. Such systems have become a need of presence era due to increase in vehicular traffic on roads.

V. PROJECT DESCRIPTION
Basic notion of this project endeavors to contribute towards dynamic traffic controllers by designing a system that uses cameras to get information of current traffic scenario of roads and on the base of congestion it notifies that  signal of which lane is to be turned green. System is designed by considering following four major points to make an efficient traffic control system
1.	Signal should be turned green for the road having congestion.
2.	Time span of green signal for congested road should also be increased than normal signal time.
3.	Minimum time delay to the roads having no congestion.
4.	No signal should be avoided or missed.
 Two algorithms are used to increase the efficiency of determining congestion on each lane. First via cascade of classifiers-trained by using Adaboost Algorithm cars are detected and road having maximum number of cars is determined, after that Frame differencing technique is used to approximate the density of cars’ presence on  roads. Hence, final action taken by system is based on the results of these two algorithms. For the time being this system is developed and run for the toy cars present on model.

VI. PROJECT OBJECTIVE
The system aims to reduce traffic congestion problems on roads and make the traffic flow smoother. Major objectives of project are:
1.  Develop a Traffic Congestion Control System.
2.  Detection of cars.
3.  Determine congestion on road.
4.  Notify which signal should be turned green.
5.  Signal for road having congestion should turn green first.
6.  Minimum delay to the signals having normal traffic. 
7.  No signal should be missed in a single lap.
8. Green signal time for congested road should be increased.

VII. PROBLEM STATEMENT
Traffic conditions on roads are getting worse due to immense increase in vehicular traffic and existing infrastructure is not capable of handling it efficiently. 

VIII. PROJECT SCOPE
An automated traffic congestion control system is designed by using image processing techniques to meet the congestion challenges and make traffic flow smoother. Focus of this project includes three main tasks :
1.	Detection of cars
2.	Determination of congestion
3.	Notify which signal should switch to green light.
          Implementation details are:
1.	Language: C
2.	Complier: Code Block
3.	Input source for system: (video from) Cameras.
4.	Output by system: Notification will appear on laptop screen that which signal should be turned green.

IX. PROJECT LIMITATION
         Following points illustrate project’s constraints   
1.	Uneven light conditions should be avoided.
2.	Project does not involve hardware part to control signals (LEDs).
3.	Cameras should take continuous video frames of roads from top view and its angle of declination should be minimum. 
4.	Cameras should be placed on fixed positions such as that they capture the frontal top view of cars. 










BACKGROUND
This chapter of thesis gives a view of some traffic control systems already existing in the world using various technologies to make traffic management efficient. Besides this the basic knowledge and terms required for further understanding of this project is also discussed within this section. 
TYPES OF EXISTING SYSTEMS
           Two fundamental types of Traffic Control Systems exist in the world
FIXED TIME TRAFFIC CONTROL SYSTEMS
These are the systems that control signals switching according to a specific time period. A time interval is set after which signals have to change no matter what is the traffic condition on any lane. They rely on “electro-mechanical signal controller” which is a less complicated signal controller and have dial timers which can keep a certain color on for a specific time [5].
DYNAMIC CONTROL SYSTEMS
Dynamic Control Systems are particularly developed to be able to adapt their settings to traffic conditions. Foundation of dynamic control system is actually a detector which communicates with the traffic lights and tells it about the traffic conditions in real time [5]. 
TYPES OF DETECTORS
With the increase in technology various types of detectors have been emerged. Following two main types of detectors are in use with Traffic control Systems in the world
1.	Embedded into road surface [5]
2.	Mounted above roads [5]
EMBEDDED INTO ROAD SURFACE
Systems use inductive loops with their control devices which inform the controller about the presence of cars on roads. These inductive loops are implanted in road surface which can be seen by observing holes on the roads. Whenever a car passes over them it informs the controller about the go by of a car and hence controller gets the information about presence of cars and is programmed to take actions on the base of information provided by the inductive loop. But this technology is expensive than other systems present in the world and it requires much installation and maintenance cost. 
MOUNTED ABOVE ROADS
These detectors are placed above the roads either on a pole or something else which can provide more real time information to controllers such as cameras. They are also easy to install and require less maintenance cost. Their maintenance is also easy and they have direct and close link with signal controller so chances of error also decrease. They can also be used for other purposes like for security checks etc. 
EXISTING SYSTEMS
Following Traffic Control Systems exist in the world which is working on the base of some latest technology, apart from fixed time controllers.
CENTRALIZED TRAFFIC CONTROL SYSTEMS
Centralized traffic control systems [6] are those in which traffic signal control equipments coordinate with a central computer that is placed far off at distant place and is being monitored by few experts who monitor the overall road traffic and can change signal timings as well. Such systems have been employed in the world and are running effective. They also help in security matters and maximize the road capacity. It also becomes easy with them to recognize and detect faults in the signal controlling equipment. 
URBAN TRAFFIC CONTROL SYSTEMS
Urban Traffic Control (UTC) System is a special traffic management system that co-ordinate and integrates traffic signals control over a wide area in order to control traffic flows on the road network [7]. It connects all signals electronically and management system is designed such as that it depends on the occurrence and individual signal aspects and the time difference between them. It utilizes some objective function to make traffic flow even, reliable and time saving.  There are further many types of UTC system
1.	Plan Selection Systems
2.	Plan Generation systems
3.	Local Adaptation
4.	Traffic Responsive Centralized Systems
5.	Traffic Responsive Systems with Distributed Processing
TRAFFIC CONTROL SYSTEM USING INDUCTIVE LOOPS
Use of inductive loops to make traffic effective traffic management system has been used widely in many countries. Via inductive loops presence of cars on roads is judged and information is sent to traffic controller. It is based on the notion of inductance transform in a coil when a metal body comes close to it. It’s also a trustworthy and cost valuable method of car detection and can be used in many traffic control systems or parking 
IMAGE PROCESSING LIBRARY
“Open Source Computer Vision Library” commonly known as OpenCV is one of the famous libraries used for real time image processing techniques. It consists of programming functions and different algorithms implementation that can be directly used by calling these functions.
DOMINANT DETECTION APPROACHES
   Different techniques have been illustrated in literature for vehicle detection.  Few of them are  as under:
1.	   Template matching  
1.	SVM based classification 
2.	Haar like features 
3.	Color based detection  
4.	Recognition on the foundation of image features such as pixel intensities and spatial difference 
5.	Haar features and Pair wise geometrical histogram
ADVANTAGES OF EFFICIENT TRAFFIC CONTROL SYSTEMS
 Proficient Traffic Control Systems are need of presence era. Following are their   advantages.
1.	Proficient Traffic Control Systems can make traffic flow smoother and reliable.
2.	Safe mobility can also be ensured via efficient Traffic Control Systems. 
3.	Fuel consumption can also be decreased, which is wasted while waiting on signals.
4.	A better Traffic Control System ensures reliable travel time.
5.	Reduce Congestion and traffic chaos.
6.	Lessen pollutants that are being generated while vehicles stop and wait on red signal.

