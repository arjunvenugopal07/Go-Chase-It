# Go-Chase-It
A four wheeled robot chasing a white ball in gazebo

### Source ROS environment
```sh
$ source opt/ros/kinetic/setup.bash
```
### Create a top-level workspace directory
```sh
$ cd /home/workspace/
$ cd mkdir catkin_ws
```
### Clone the repository in /home/workspace/catkin_ws/
```sh
$ cd /home/workspace/catkin_ws/
$ git clone https://github.com/arjunvenugopal07/Go-Chase-It src
```
### Initialize catkin workspace
```sh
$ cd src
$ catkin_init_workspace
```
### Compile code and source package environment
```sh
$ cd /home/workspace/catkin_ws
$ catkin_make
$ source devel/setup.bash
```
### Launch the world file
```sh
$ roslaunch my_robot world.launch
```
### Open new terminal and launch the ball chaser file
```sh
$ source opt/ros/kinetic/setup.bash
$ cd /home/workspace/catkin_ws
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch
```
