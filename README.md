# README

## Environments
* Ubuntu 18.04
* ROS melodic

## How to build

```bash
  $ mkdir -p ws/src
  $ cd ws
  $ catkin init
  $ wget https://raw.githubusercontent.com/chikuta/premaidai_moveit/master/premaidai_moveit.rosinstall .rosinstall
  $ rosinstall .
  $ catkin build
```

## How to launch

```bash
  $ cd ws
  $ source devel/setup.bash
  $ roslaunch premaidai_moveit_config demo.launch
```