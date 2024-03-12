# DeepField Workshop 2022+2023

Exploiting (supervised) learning-
based detectors for on-board,
real time localization and target
tracking

## Installation:

1. Clone repository with submodules (git clone --recursive)
2. Install ROS noetic on Ubuntu 20.04 LTS

## Tutorial:

Task: Detect and localize a cup with a simulated robot (using the laptop webcam) 

* install requirements (ROS noetic)
* run network detection server
* run detection and tracking with launch file packages/simulation/aircap/launch/detect_cup_with_webcam.launch
* have neural network detector (pytorch) detect the cup and localize in ROS
* visualize with rviz deefield_workshop.rviz

# Folders:

* ./Slides: lecture slides and system presentation
* ./ssd_pytorch_code - submodule - python code for neural network detector service - used by AirCap simulation tutorial code
* ./AirCap_code - submodule - Simulation Tutorial Source Code - bases for exercise
