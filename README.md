# ROSinGrasshopper
Collection of Tutorials for integrating [ROS](https://www.ros.org/) in [grasshopper3d ](https://www.grasshopper3d.com/); based on [docker](https://www.docker.com/), [compas fab](https://gramaziokohler.github.io/compas_fab/latest/overview.html), [bengesht](https://www.food4rhino.com/en/app/bengesht), etc.

These methods facilitates design to robotic production workflows as well as real-time and adaptive robotic fabrication workflows.
 
## Why Real-time feedback for Robotic Fabrication?
>
>According to [Association for Robots in Architecture](https://www.robotsinarchitecture.org/wp-content/uploads/2011/09/realtimerobot_ecaade2012_100.content.pdf):
>
>Industrial robotic applications usually deal with a
fabrication problem in such a way that a problem is
defined, a solution programmed and the resulting
control data file executed at the robot. Interaction
within this process is not necessary because the design is usually finished at the point when robot code
is generated.
>
> We therefore argue that robotic arms
have not yet been used to their full capabilities in industry applications, as they are never linked directly
to a design process.
>
>In our research we focus on *intuitive robot control* and *intuitive simulation* for a bottom up design
process. To develop fluent *action and reaction*
scenarios for industrial robots in an architectural
context we focus on dynamic processes in which the robot interacts with continuously changing data, resulting
in a comparably unconstrained system that cannot
be automatically solved.

>["An Art of Connectivity"](https://www.researchgate.net/publication/307996374_An_Art_of_Connectivity): Tristan Gobin, Sebastian Andraos, Thibault Schwartz of HAL robotics.
>![artOfConnectity](00-HelloWorld%20in%20Docker/media/ArtOfConnectivity.jpg)

## How does ROS work with Docker?

>![dockerfile](00-HelloWorld%20in%20Docker/media/Dockerfile.jpg)


# Requirements

- Operating System: You can use Mac or Windows 10 operating systems for most of the tutorials. However, Windows 10 is suggested for better compatibility with Grasshopper. 
- [Docker desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
    - [Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) for Visual Studio Code
- [Rhinoceros](https://www.rhino3d.com/download/) and [Grasshopper 3D](https://www.grasshopper3d.com/)
    - [GhPython](https://www.food4rhino.com/en/app/ghpython)
    - [Bengesht](https://www.food4rhino.com/en/app/bengesht)
- [Anaconda](https://www.anaconda.com/)
- [Compas Fab](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html)
    - [Compas Fab for Rhino/Gh](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html#working-in-rhino-1)

# Installation
- Install Docker Desktop
- [Install Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview)
- [Install Docker extention for Visual Studio Code](https://code.visualstudio.com/docs/editor/extension-marketplace)
- Install Rhino and Grasshopper
- [Install GhPython and Bengesht Plugins for Grasshopper](https://parametricbydesign.com/grasshopper/tutorials/installing-grasshopper-and-plugins/#2-install-by-copying-into-the-components-folder)
- Install Anaconda
- [Install Compas_Fab](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html#install-with-conda-1)

# Usage

Each tutorial is described separately inside their respective folders.

# Acknowledges 
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
