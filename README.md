# UAV-Target-Recognition-And-Tracking
In recent years, UAV began to appear in all aspects of production and life of human society, and has been widely used in aerial photography, monitoring, security, disaster relief and other fields. For example, UAV tracking can be used for urban security, automatic cruise to find suspects and assist in intelligent urban security management.However, the practical application of UAV in various early scenes was mostly based on human remote control or intervention, and the degree of automation was not high. The degree to which UAVs can be automated is one of the decisive factors in whether they can play a bigger role in the future. With the increasing demand of UAV automation, target tracking based on computer vision has become one of the current research hotspots. Some companies in China and abroad, such as DJI, have successfully equipped target tracking on UAVs, but these technologies only exist in papers and descriptions, and the specific implementation has not been sorted out and opened source. Therefore, we plan to try to complete this project by ourselves and open source it on Github. Traditional visual tracking has many advantages, such as strong autonomy, wide measurement range and access to a large amount of environmental information, it also has many disadvantages.It requires a powerful hardware system. In order to obtain accurate navigation information, it needs to be equipped with a high-resolution camera and a powerful processor. From image data acquisition to processing, huge data operations are involved, which undoubtedly increases the cost of UAV tracking. Moreover, the reliability of traditional visual navigation and tracking is poor, and it is difficult for UAV to work in complex lighting and obstacle scenes. Therefore, we plan to use deep learning for target tracking in this project. We can train our own model through deep learning algorithm (we have not decided what network structure to use), then move the trained model to the embedded development board for operation, fix it on the UAV, read the image through the camera and process the data, so that it can recognize the objects to be recognized and tracked. In this project, we will use NVIDIA Jetson TX2 development board, install ROS in Linux system, establish communication with pixhawk, and conduct UAV flight control through PID algorithm.
