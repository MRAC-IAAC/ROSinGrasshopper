FROM ros:melodic

RUN apt-get update && \
    apt-get install -y ros-melodic-rosbridge-suite && \
    apt-get install -y ros-melodic-ros-tutorials && \
    apt-get install -y ros-melodic-common-tutorials && \
    # Clear apt-cache to reduce image size
    rm -rf /var/lib/apt/lists/*

