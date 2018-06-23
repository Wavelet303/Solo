# Solo
This is the darknet base segmentation platform with deep neural network and It also have the ability to perform object detection and segmentation at the same time. In the iNES lab of Gachon University, we worked on this idea and we successfully got efficient results. In the same hand, our new network is computationally better and faster than Segnet,FCN, and Yolo family. Therefore, we would like to share all the essential knowledge regarding to it. Later on, we'll extend our network for 3D segmentation, and object detection to completely apply in self driving cars.
# Description
As we know that darknet base yolo is the world fastest object detection algorithm and we actually added our own layers in the yolo to convert yolo into solo. We remove some extra burden layers from yolo so that we can optimized form of our new network. We also designed our own Intersection of Segments(IOS) function and try to implement it.
# How to run
1) Please clone this repository to your system and before run it make sure, you have successfully install the support of opencv, and navidia gpu.

2) For installing darknet please follow the original command from the site. This is the link of it: https://pjreddie.com/darknet/install/

# Results
# Comparision with Segnet, FCN, and other segmentation networks.
