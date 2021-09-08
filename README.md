# Map-My-World-Robot
Udacity Robotics Software Engineer Nanodegree Map My World Robot Project:

### Install
Clone the repo
``
cd /home/workspace/catkin_ws/src/udacity_bot``    
``git clone https://github.com/ayertay/Map-My-World-Robot.git``    
``catkin_make``    
``source devel/setup.bash``
### Running the Scripts
Run the following commands below in separate terminals: 

``
cd /home/workspace/catkin_ws``    
``catkin_make``   
``source devel/setup.bash``

Launch the world in Gazebo and RViz:  
`` cd /home/workspace/catkin_ws/``  
``roslaunch udacity_bot world.launch``  
Launch the AMCL node for localization:  
``roslaunch udacity_bot localization.launch``  
