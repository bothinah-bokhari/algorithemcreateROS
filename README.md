# algorithemcreateROS
1-Setup sources.list
2-Set up your keys
3-Installation 
4-Desktop-Full Install
5-test if ROS has installed by writing "roscore"


algorithm to install ROS on Jetson Nano :
1-git clone https://github.com/JetsonHacksNano/installROS.git
2-cd installROS/
3-./installROS.sh
4-./installROS.sh -p ros-melodic-desktop
5-#setupCatkinWorkspace.sh
6-./setupCatkinWorkspace.sh
7-gedit ~/.bashrc
8-source ~/.bashrc
9-roscore
#TRY THIS TO ENSURE RUNINIG:
10-rostopic list 
