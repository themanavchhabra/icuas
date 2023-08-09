# Exploration of GPS-denied environment to detect and segment cracks in an Indoor Environment
 		
Developed obstacle avoidance algorithm in ROS to guide and map a UAV across an uncharted territory using a depth camera and IMU as sensors while operating in a GPS-denied environment. 

YoloV7 has been used to detect cracks in the indoor environment. A modified U2NET model has been utilised to segment the cracks.

It consists of your original package which has been modified by us according to your needs. We have modified the `session.yaml`and the Dockerfile, so that it builds and installs all the dependencies. The given `start.sh` can be used to launch the simulation.

The *custom_packages* folder contains the packages that were heavily modified by us to be used in this simulation. These packages must be placed in the *uav_ws/src* folder, and `catkin b` be used to build the packages.

In case of any errors, please contact

Manav Chhabra - manavrchhabra@gmail.com
(Software Technician, UAS-DTU)

Arjun Gupta - arjun222gupta@gmail.com
(Avionics Technician, UAS-DTU)
