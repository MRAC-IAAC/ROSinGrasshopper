# ROSinGrasshopper
Tools for integrating ROS in grasshopper3d; based on docker, compas_fab, bengesht, etc.


This repository contains tutorials for two different approaches to integrate [ROS](https://www.ros.org/) (Robotic Operating System) as a backend software for [Grasshopper3D ](https://www.grasshopper3d.com/)(Algorithmic modeling tool for Rhinoceros). These methods facilitates design to robotic production workflows as well as real-time and adaptive robotic fabrication workflows.

## Projects

**[Robotic Mosaic](http://www.iaacblog.com/programs/w-2-1-syllabus-faculty-2/):**
Computational design and robotic fabrication processes based on available materials, computer vision and real-time robotic fabrication.
The workflow utilizes automatic path planning algorithm packages in ROS for an industrial arm robot ([UR10e](https://www.universal-robots.com/products/ur10-robot/)), as well as computer vision algorithms with python OpenCV, to process images from an intel realsense camera for a real-time robotic fabrication setup. Technically we use Docker to run several ROS nodes and utilse [COMPAS FAB](https://gramaziokohler.github.io/compas_fab/latest/overview.html) to interact with them in Grasshopper3d.

**[Drawing Bot](http://www.iaacblog.com/programs/the-drawing-bot/):**
Utilizing rover robots ([Turtlebot](https://www.turtlebot.com/)) to draw construction instructions on-site based on computationally drawn inputs.


## Repository structure
Each project is documented separately inside their respective folders for the installation guide and usage tutorials.



## Acknowledges 
<!-- 
    ROSIN acknowledgement from the ROSIN press kit
    @ https://github.com/rosin-project/press_kit
-->

More details: <a href="https://iaac.net/rosin-new-robotic-setup/"> in this link. </a>

<a href="http://rosin-project.eu">
  <img src="http://rosin-project.eu/wp-content/uploads/rosin_ack_logo_wide.png" 
       alt="rosin_logo" height="60" >
</a>

Supported by ROSIN - ROS-Industrial Quality-Assured Robot Software Components.  
More information: <a href="http://rosin-project.eu">rosin-project.eu</a>

<img src="http://rosin-project.eu/wp-content/uploads/rosin_eu_flag.jpg" 
     alt="eu_flag" height="45" align="left" >  
