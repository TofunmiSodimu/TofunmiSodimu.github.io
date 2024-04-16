#### Kelp Segmentation 
This project is concerned with the development of a model that can map and detect kelp forests (an ocean community made up of dense groupings of kelps) in satellite images, in order to empower conservation efforts. The satellite images were processed and used to calculate the Normalized Difference Water Index (NDWI) and Normalized Difference Vegetation Index (NDVI) parameters that are useful in detecting the presence/absence of vegetation. These values, as well as the Near Infrared channel values, were then used to train a U-Net semantic segmentation model that outputs a masked image (kelp or no kelp).

##### Skills/FrameWorks/Tools Used: Python programming, Convolutional Neural Networks, Deep Learning

[Kelp Segmentation Repo](https://github.com/nadira30/kelp_segmentation)
<br/><br/>

#### Anomaly Detection of Object Locations
By being able to detect when an object is an unusual location, we can optimize the system described in the 'Robotic Assistsant for Finding Misplaced Objects' project to premptively identify misplaced ojects, and to take certain follow-up actions. For this project, I have developed a CNN model that is trained on scene graphs of a person's household routine over 50 days (HOMER-PLUS Dataset - https://github.com/Maithili/HOMER_PLUS/tree/main). The model's output indicates whether an object is in anomlaous location or not. Please see the Github repo for more info on the project. 

##### Skills/FrameWorks/Tools Used: Python programming, Convolutional Neural Networks, Deep Learning

[Anomaly Detection Repo](https://github.com/TofunmiSodimu/Novelty-Detection)
<br/><br/>

#### Robotic Assistant for Finding Misplaced Objects
Mild Cognitive Impairment (MCI) is an early-stage decline in memory, language perception, visual perception, and/or other cognitive abilities that is greater than expected for an individual’s age and education level, but that does not greatly impact their ability to perform everyday activities. Research has shown that this condition is present in 3-19% of people over the age of 65. One common symptom of this condition is misplacing objects due to the inability to recall where the item was last kept. To address this issue, we developed a robot to keep track of commonly misplaced objects and recall their location upon request. In our implementation, the robot routinely navigates the home based on a pre-generated map and captures images of the surfaces found at each of the pre-set waypoints. These images are passed through an object classification model to identify the items within them. The names of the identified objects, timestamp, and location are stored in a JSON database. Upon request by the user, the database is scanned for all instances of the missing object, and the associated images are displayed on a screen for the user to confirm that it is indeed the object they are searching for. Finally, the robot leads the user to the object’s location and points at it.

##### Skills/FrameWorks/Tools Used: Python programming, Robotic Operating System (ROS), Hello Robot Stretch RE2, Object Detection Models

[Robotic Assistant Repo](https://github.com/JuanRobledo12/blue_stretch)
<br/><br/>

[![Video describing process](static/assets/img/THUMBNAIL.png)](https://www.youtube.com/watch?v=QUB79UTbwvE)

<br/><br/>

#### Path Planning to Control Robotic Arm for Suturing

[Path Planning Repo](https://amritpal-001.github.io/projects/2022-medical-robotics-kinematics)

<br/><br/>

##### Skills/FrameWorks/Tools Used: MATLAB, Arduino, Mechanics, Forward/Inverse Kinematics, Computer Aided Design (CAD)

#### Bladder Fluid Flowscope
- Developed the electrical schematic and implemented the circuitry for the device enabling us to measure volumes of 0 – 1000mL with an accuracy of +/- 4mL per our client’s specifications.
- Developed an Arduino program to determine volume based on the voltage signal from the load cell and the density of the fluid, and to display the calculated volume, to the nearest mL, in real time.
- Provided effective leadership for a group of 5 students leading to the successful completion of the project.
- Maintained regular and effective communication between client, team mentor, and team members.

##### Skills/FrameWorks/Tools Used: Arduino, Mechanics, Computer Aided Design (CAD)
