FROM osrf/ros:melodic-desktop-full

RUN apt-get update && apt-get install -y \
    ros-melodic-rosbridge-suite \
    ros-melodic-turtlesim && \
    # Clear apt-cache to reduce image size
    rm -rf /var/lib/apt/lists/*

