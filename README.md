# Mobilenet_Jetson
#2018.12.4 Wenbo Bian
1.Configuration
Hardware：Jetson TX2
Software：#see jetson TX2_configuration_setting_1.0.docx
Cuda8.6
Cudnn
Opencv3.4.0
Tensorflow1.3.0
Caffe-ssd
Mxnet1.1.0
2.Network Specification
(1) face detect  #tensorflow
(2) face detect extract  #opencv+mxnet
(3) pedestrian detect  #caffe-ssd
(4) pedestrian detect extract  #mxnet
3.main.py
Face recognition
Pedestrian recognition
Face feature extraction
Pedestrian feature extraction
Face and Pedestrian Recognition
A Camera monitor the people number for entering and exiting
Save frames that successfully identify front or back
4. Edition
1.0+1.1 camera only monitors entrance
2.0+2.1+2.2 entering and exiting, but it exists bug
3.1+3.2 functional integrity
5. warning
Caffe and cam_observer in a common filedir
