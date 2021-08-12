# use-another-ROS-robot-with-SLAM-approach-
## task4
 
---

- This will work with ubuntu 18.04 and ROS melodic

---

- 1st: run this code in the terminal.

`sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation`

---

- 2nd: run this code in the terminal:

``
cd ~/catkin_ws/src
git clone https://github.com/wh200720041/warehouse_navigation.git
cd ..
catkin_make
source ~/catkin_ws/devel/setup.bash
``

---

- last step is launch ROS by running this code: 

`roslaunch warehouse_simulation warehouse_simulation.launch`

---

![IMG_6999](https://user-images.githubusercontent.com/85639068/129168796-6e4647b0-f3be-4064-8438-2377083772db.jpg)


---

- here is some pictures of how it work with me: 

---

![IMG_7002](https://user-images.githubusercontent.com/85639068/129168321-7eb9d024-e2b3-4140-9961-4e5da30122c0.jpg)

---

![IMG_7001](https://user-images.githubusercontent.com/85639068/129168342-8a2d4711-f1de-4ef4-b35e-76e2db278a06.jpg)

---
