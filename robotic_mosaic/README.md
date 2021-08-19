## Requirements
- [Docker desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
    - [Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) for Visual Studio Code
- [Rhinoceros](https://www.rhino3d.com/download/) and [Grasshopper 3D](https://www.grasshopper3d.com/)
    - [GhPython](https://www.food4rhino.com/en/app/ghpython)
- [Anaconda](https://www.anaconda.com/)
- [Compas Fab](https://gramaziokohler.github.io/compas_fab/latest/getting_started.html)

## Installation

### ROS setup in Docker
- clone the `robotic_mosaic` folder
- build the docker image using Dockerfile
    - in VSCode press `ctrl+shift+p` then type `Docker images: Build image`
    - enter a name for the image *("image_name":"tag")*: `roboticmosaic:latest`  


## Usage
### Run your ROS nodes with Docker 
- open the `robotic_mosaic` folder in VSCode  
- run multiple containers from the built image using the `docker-compose.yml` using VSCode terminal
    - docker-compose up -d


## Technical References
 
 [Docker compose in ROS](http://wiki.ros.org/docker/Tutorials/Compose)
 
