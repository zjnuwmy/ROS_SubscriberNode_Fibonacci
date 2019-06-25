# ROS_SubscriberNode to get Fibonacci list

download from this page
```download from this page
cd catkin_ws/src
git clone https://github.com/zjnuwmy/ROS_SubscriberNode_Fibonacci
cd ..
catkin_make
source devel/setup.bash
```

Just run linsener.py
```rosrun mypkg linstener.py```

One more thing:
Please make sure roscore is run in a new terminal```roscore```

If you want test the code just run```rostopic pub fib std_msgs/Int16 12```in a new terminal
