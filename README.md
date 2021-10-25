# custom_maps

To run the maps, first clone the package from source into a folder i.e. catkin_ws/src 

  mkdir -p ~/catkin_ws/src
  
  cd catkin_ws/src
  
  git clone https://github.com/HParsons3/custom_maps.git
  
Then run catkin_make in the root directory.

  cd catkin_ws
  
  catkin_make
  
Source the setup file in the devel folder

  source devel/setup.bash
  
launch the world file you want

  roslaunch custom_maps map3.launch
