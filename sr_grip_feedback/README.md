#Grip Feedback Demo
This is a simple demo of the lite hand's grip feedback data.

##Dependencies
1. Shadow robot ROS development environment, installed using the one-liner
2. [rqt_multiplot](https://github.com/ethz-asl/rqt_multiplot_plugin) and it's dependencies

##Installation
1. Check out into your_catkin_workspace/src
2. `catkin_make`
3. `roslaunch sr_grip_feedback sr_grip_feedback.launch`
4. In the multiplot window within rqt, browse to the included config (`perspectives/mulitplot/hand_feedback_demo.xml`)
