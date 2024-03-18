# rf2o_laser_odometry_holonomic for ros2 humble

Originally forked from MapirLAB. <link> http://mapir.isa.uma.es/mapirwebsite/index.php/mapir-downloads/papers/217 </link>

I speculate that the origin of this package is to be used with differential-drive robots. When tested, it does not produce the right linear speed y. 

I modified it so it can be used with the holonomic robot, which needs odometry calculation for linear speed in the y-axis. This will help the move_base navigation stack later

 A simple echo to the topic /odom is shown below:
![image](https://github.com/simbolonmartin/rf2o_laser_odometry_holonomic/assets/40651935/0270540d-870c-4463-84f1-d9e8868944c2)