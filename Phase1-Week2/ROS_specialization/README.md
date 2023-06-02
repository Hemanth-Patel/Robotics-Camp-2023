# ROS specialization



*__Welcome to the ROS specialization by Robotics Club, IIT(BHU) Varanasi. We Aim is to deliver structered Beginner Level Understanding of ROS to get you started with projects so Get ready to dive into the thrilling world of Robot Operating System (ROS) – the ultimate brain behind our mechanical pals! ROS is the secret sauce that brings robots to life, turning them into your very own loyal sidekicks. With ROS, you'll unlock a world of endless possibilities and become the master of your own robot army. So, put on your lab coat and get ready to unleash the power of ROS – let the robotic revolution begin!__*

<img src= "https://github.com/panchal-harsh/Robotics-Camp-2023/blob/main/Phase1-Week2/ROS_specialization/images/MEME1.jpg" width=65% height =65%>


## What is ROS

___ROS(Robot Operating System) is a software framework to enable communication, data flow, and suitable infrastructure development for a hardware-software system (robotics being the best application).
Oh, wait! It is also technically not an operating system. ROS is an OS only in concept because it provides all the services that any other OS does — hardware abstraction, low-level device control, implementationof commonly-used functionality, message-passing between processes, and package management. But, ROS is a framework on top of the OS that allows it to abstract the hardware from the software. This means you can think in terms of software for all the hardware of the robot.
And that’s good news for you because this implies that you can actually create programs for robots without having to deal with the hardware. Cool right!___
ROS makes it easy to get a robot running and do the required task.
These are the lines from the original paper :

>Writing software for robots is difficult, particularly as the scale and scope of robotics continues to grow. Different types of robots can have wildly varying hardware, making code reuse nontrivial. On top of this, the sheer size of the required code can be daunting, as it must contain a deep stack starting from driver-level software and continuing up through perception, abstract reasoning, and beyond. Since the required breadth of expertise is well beyond the capabilities of any single researcher, robotics software architectures must also support large-scale software integration efforts.

>To meet these challenges, many robotics researchers, including ourselves, have previously created a wide variety of frameworks to manage complexity and facilitate rapid prototyping of software for experiments, resulting in the many robotic software systems currently used in academia and industry. Each of these frameworks was designed for a particular purpose, perhaps in response to perceived weaknesses of other available frameworks, or to place emphasis on aspects which were seen as most important in the design process.

>ROS is also the product of tradeoffs and prioritizations made during its design cycle. We believe its emphasis on large-scale integrative robotics research will be useful in a wide variety of situations as robotic systems grow ever more complex

Because next time you have to use a hand manipulator to grasp your smiley ball, or make a Bayesian Map using depth Camera and IMU you need not heatup the battery of your calculator nor ... 






 ## What are we going to cover?
 * ### ROS Communication
We would be explaining the basics of ROS in which we would be explaining a basic structure of a ROS package/application. We will also cover ROS master, Nodes, Topics, Messages and Services

* ### RViz and Gazebo
Introduction to Debugging/Visualizing Elements and softwares that ROS offers along with Brief Introduction of Simulation is ROS with Gazebo


* ### Mapping and localisation
we will discuss and implement  different mapping and localisation techinques 

* ### creating a node of our own
Here we will discuss how can we create workspaces, build packages and write a subscriber and publisher node from scratch 


NOTE: ***We recommand you to look up [ros wiki](http://wiki.ros.org/Documentation) and [ros answers](https://answers.ros.org/questions/) as they contain literally everything from where most of us have learnt ROS.***     

Why is ROS so famous?
Because there are thousands of open source packages that work on ROS and can do task from as small as simulating a turtle bot to drive a full fleged autonomous car you just for example to map an environment in simulation you just need to execute following and you are good to go....

$ sudo apt-get install ros-openslam-gmapping
$ roslaunch gmapping gmapping.launch
...
....
......[process-started] Node launched

![](https://github.com/panchal-harsh/Robotics-Camp-2023/blob/main/Phase1-Week2/ROS_specialization/images/mappp.gif)




Before starting I would highly recommand you to go through important and useful linux command at [linuxcommand.md](https://github.com/panchal-harsh/Robotics-Camp-2023/blob/main/Phase1-Week2/ROS_specialization/linuxcommands.md) after this you are all set to start with ROS communication Happy learning...!











<p align="center"> This track was contributed by <a href="https://github.com/panchal-harsh">Harsh Panchal</a> </p>
 

