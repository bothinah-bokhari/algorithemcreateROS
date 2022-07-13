# algorithemcreateROS
Setup sources.list
Set up your keys
Installation 
Desktop-Full Install
test if ROS has installed by writing "roscore"


algorithm to install ROS on Jetson Nano :
git clone https://github.com/JetsonHacksNano/installROS.git
cd installROS/
./installROS.sh
./installROS.sh -p ros-melodic-desktop
#setupCatkinWorkspace.sh
./setupCatkinWorkspace.sh
gedit ~/.bashrc
source ~/.bashrc
roscore
#TRY THIS TO ENSURE RUNINIG:
rostopic list 
