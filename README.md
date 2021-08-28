# ROSinGrasshopper

Collection of Tutorials for integrating [ROS](https://www.ros.org/) in [grasshopper3d](https://www.grasshopper3d.com/); based on [docker](https://www.docker.com/), [compas fab](https://gramaziokohler.github.io/compas_fab/latest/overview.html), [bengesht](https://www.food4rhino.com/en/app/bengesht), etc.

These methods facilitates design to robotic production workflows as well as real-time and adaptive robotic fabrication workflows.

## What is Real-time feedback for Robotic Fabrication?
>
>According to [Association for Robots in Architecture](https://www.robotsinarchitecture.org/wp-content/uploads/2011/09/realtimerobot_ecaade2012_100.content.pdf):
>
>Industrial robotic applications usually deal with a
fabrication problem in such a way that a problem is
defined, a solution programmed and the resulting
control data file executed at the robot. Interaction
within this process is not necessary because the design is usually finished at the point when robot code
is generated.
> We therefore argue that robotic arms
have not yet been used to their full capabilities in industry applications, as they are never linked directly
to a design process.
>
>In our research we focus on *intuitive robot control* and *intuitive simulation* for a bottom up design
process. To develop fluent *action and reaction*
scenarios for industrial robots in an architectural
context. Focusing on dynamic processes in which the robot interacts with continuously changing data, resulting
in a comparably unconstrained system that cannot
be automatically solved.

![artOfConnectity](00-HelloWorld%20in%20Docker/media/ArtOfConnectivity.jpg)

>["An Art of Connectivity"](https://www.researchgate.net/publication/307996374_An_Art_of_Connectivity): Tristan Gobin, Sebastian Andraos, Thibault Schwartz of HAL robotics.

## How do I use ROS with Docker?

**Dockerfile** uses our recipe for the image we want to create and creates an [ubuntu] image. 
Here we can choose the ROS version we want to use, which packages we want to install, etc.

![dockerfile](00-HelloWorld%20in%20Docker/media/Dockerfile.jpg)

**Docker-Compose** is used to run custom/different applications from our image. By defining which ROS nodes we like to run together.

![docker-compose](00-HelloWorld%20in%20Docker/media/docker-compose.jpg)

## Requirements

- Operating System: You can use Mac or Windows 10 operating systems for most of the tutorials. However, Windows 10 is suggested for better compatibility with Grasshopper. 
- [Docker desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Rhinoceros](https://www.rhino3d.com/download/) and [Grasshopper 3D](https://www.grasshopper3d.com/)
  - [GhPython](https://www.food4rhino.com/en/app/ghpython)
  - [Bengesht](https://www.food4rhino.com/en/app/bengesht)
  - [ROS.GH](https://github.com/behrooz-tahanzadeh/ROS.GH)
- [Anaconda](https://www.anaconda.com/)

## Installation

- Install Docker Desktop
- [Install Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview)
  - [Install Docker extention for Visual Studio Code](https://code.visualstudio.com/docs/editor/extension-marketplace)
- Install Rhino and Grasshopper
  - [Install the Plugins for Grasshopper](https://parametricbydesign.com/grasshopper/tutorials/installing-grasshopper-and-plugins/#2-install-by-copying-into-the-components-folder)
- Install Anaconda
  - [Install Compas_Fab](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html#install-with-conda-1)
  - [Install Compas Fab for Rhino/Gh](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html#working-in-rhino-1)

## Usage

Each tutorial is described separately inside their respective folders.

## Acknowledges

<!-- 
    ROSIN acknowledgement from the ROSIN press kit
    @ https://github.com/rosin-project/press_kit
-->

More details: [in this link](https://iaac.net/rosin-new-robotic-setup/).

<a href="http://rosin-project.eu">
  <img src="http://rosin-project.eu/wp-content/uploads/rosin_ack_logo_wide.png" 
       alt="rosin_logo" height="60" >
</a>

Supported by ROSIN - ROS-Industrial Quality-Assured Robot Software Components.  
More information: [rosin-project.eu](http://rosin-project.eu)

<img src="http://rosin-project.eu/wp-content/uploads/rosin_eu_flag.jpg" 
     alt="eu_flag" height="45" align="left" >  
