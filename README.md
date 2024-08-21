# pcd2bag

This is a simple tool generated by ChatGPT for converting point cloud data (`*.pcd`) files into one rosbag (`*.bag`) with a subscribed topic: /point_cloud.

## Get started

Open an terminal and run:
```
cd ~/your/workspace/
git clone https://github.com/YukiKuma111/pcd2bag.git
cd pcd2bag/src/
catkin_init_workspace
cd ..
catkin_make
source devel/setup.bash
```

## Run

```
rosrun pcd_to_rosbag pcd_to_rosbag /your/input/pcd/directory output/rosbag/save/path/output.bag
```

## File directory
```
.
├── README.md
└── src
    └── pcd_to_rosbag
        ├── CMakeLists.txt
        ├── include
        │   └── pcd_to_rosbag
        ├── package.xml
        └── src
            └── pcd_to_rosbag.cpp
```