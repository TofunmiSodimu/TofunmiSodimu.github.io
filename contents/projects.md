
#### Robotic Assistant for Finding Misplaced Objects
Mild Cognitive Impairment (MCI) is an early-stage decline in memory, language perception, visual perception, and/or other cognitive abilities that is greater than expected for an individual’s age and education level, but that does not greatly impact their ability to perform everyday activities. Research has shown that this condition is present in 3-19% of people over the age of 65. One common symptom of this condition is misplacing objects due to the inability to recall where the item was last kept. To address this issue, we developed a robot to keep track of commonly misplaced objects and recall their location upon request. In our implementation, the robot routinely navigates the home based on a pre-generated map and captures images of the surfaces found at each of the pre-set waypoints. These images are passed through an object classification model to identify the items within them. The names of the identified objects, timestamp, and location are stored in a JSON database. Upon request by the user, the database is scanned for all instances of the missing object, and the associated images are displayed on a screen for the user to confirm that it is indeed the object they are searching for. Finally, the robot leads the user to the object’s location and points at it.

- Co-developed an innovative robotic system dedicated to aiding individuals with Mild Cognitive Impairment in locating misplaced objects.
- Programmed a Stretch RE2 robot to adeptly capture images from varied angles, leveraging a pre-trained object detection algorithm for accurate classification.
- Co-implemented a JSON database for object information storage and retrieval.
- Demonstrated effective problem-solving skills for a user-friendly solution.
- [Github](https://github.com/JuanRobledo12/blue_stretch)

[![Video describing process](static/assets/img/THUMBNAIL.png)](https://www.youtube.com/watch?v=QUB79UTbwvE)

<iframe style="display: block; margin: auto;" width="560" height="315" src="https://www.youtube.com/watch?v=QUB79UTbwvE" frameborder="0" allowfullscreen></iframe>

#### Path Planning to Control Robotic Arm for Suturing
[Please see the linked page](https://amritpal-001.github.io/projects/2022-medical-robotics-kinematics)

#### Bladder Fluid Flowscope, Senior Design Project Fall 2021 – Spring 2022
- Developed the electrical schematic and implemented the circuitry for the device enabling us to measure volumes of 0 – 1000mL with an accuracy of +/- 4mL per our client’s specifications.
- Developed an Arduino program to determine volume based on the voltage signal from the load cell and the density of the fluid, and to display the calculated volume, to the nearest mL, in real time.
- Provided effective leadership for a group of 5 students leading to the successful completion of the project.
- Maintained regular and effective communication between client, team mentor, and team members.
<p align="center">
  <img src="static/assets/img/senior design showcase.jpeg" alt="Flowscope" width="500"/>
</p>
