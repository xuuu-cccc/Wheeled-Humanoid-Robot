
# TIB 

**TIB** 是由天津大学与通智人工智能有限公司联合发起的开源仿人形轮式智能机器人仿真平台，聚焦具身智能的人机协同、环境感知与自主决策，面向教育、服务与科研等场景，提供可复用的技术方案与实践参考。

## 目录

 * [开发环境](#开发环境)
 
 * [基本功能](#基本功能)
 
   * [摄像头图像采集与识别](#1-摄像头图像采集与识别)
   
   * [图像预处理与智能识别](#2-图像预处理与智能识别)
 
   * [激光雷达数据采集与显示](#3-激光雷达数据采集与显示)
   
   * [运动姿态数据采集与展示](#4-运动姿态数据采集与展示)
   
   * [多源感知数据融合](#5-多源感知数据融合)
 
   * [机械臂抓取控制](#6-机械臂抓取控制)
  
   * [自主路径规划与导航](#7-自主路径规划与导航)
   
   * [强化学习算法训练与应用](#8-强化学习算法训练与应用)
  
 * [贡献者](#贡献者)

### 开发环境

- Ubuntu 24.04

- ROS 2 Jazzy

- Gazebo Harmonic
  
### 基本功能

#### 1. 摄像头图像采集与识别
    
  MTIB 配备高清相机，可实时采集环境图像信息，实现对目标物体的识别等多种功能。<br>
    
  在代码实现上，相关程序位于 `###` ,运行`###`脚本可启动相机采集图像。<br>
 
 #### 2. 图像预处理与智能识别
    
  借助 OpenCV 库进行图像处理，如图像滤波、边缘检测等，同时结合深度学习模型提升图像识别的准确性和鲁棒性。

 #### 3. 激光雷达数据采集与显示
    
  激光雷达用于获取环境的三维点云数据，帮助机器人感知周围物体的距离和形状。​

 #### 4. 运动姿态数据采集与展示
    
  IMU（惯性测量单元）可采集机器人的加速度、角速度等运动状态数据，用于机器人的姿态估计。

 #### 5. 多源感知数据融合
   
  将相机、激光雷达、IMU 等多种传感器的数据进行融合，综合利用各传感器的优势，提高机器人对环境感知的准确性和可靠性。
 
 #### 6. 机械臂抓取控制
    
   TIB 配备了多自由度机械臂，能够完成对不同形状、大小物体的抓取操作，可应用于物品搬运、装配等场景。

 #### 7. 自主路径规划与导航
  
   TIB 具备自主导航功能，能够在环境中构建地图、规划路径并避开障碍物，自主到达指定目标点。

 #### 8. 强化学习算法训练与应用
   
  为了提升 TIB 在复杂环境中的适应能力和决策性能，项目引入强化学习技术，通过不断与环境交互学习，优化机器人的行为策略。

### 贡献者
  
  感谢以下人员对本项目的贡献：<br>
  
 徐晨 xuc@tju.edu.cn；
 王亚茹 ；
 陈曦 chenxi@tju.edu.cn；
 原续波 xbyuan@tju.edu.cn；
 吴红啸 WHXwhx12305@163.com;
 李明益 limingyi@bit.edu.cn;
 李嘉伟 18247395676@163.com.

 




# TIB

**TIB** is an open-source humanoid wheeled robot simulation platform jointly launched by Tianjin University and Tongzhi AI Co., Ltd. focusing on embodied intelligence in human–robot collaboration, environmental perception, and autonomous decision-making. It provides reusable technical solutions and practical references for education, service, and research applications.


 
## Content

   - [System Requirements](#system-requirements)
   - [Features](#features)
      - [Camera-Based Image Acquisition and Recognition](#1-camera-based-image-acquisition-and-recognition)
      - [OpenCV and Deep Learning Integration](#2-opencv-and-deep-learning-integration)
      - [LiDAR Data Acquisition and Visualization](#3-lidar-data-acquisition-and-visualization)
      - [Motion and Posture Data Acquisition and Display](#4-motion-and-posture-data-acquisition-and-display)
      - [Multisource Sensor Fusion Perception](#5-multisource-sensor-fusion-perception)
      - [Robotic Arm Manipulation Control](#6-robotic-arm-manipulation-control)
      - [Autonomous Path Planning and Navigation](#7-autonomous-path-planning-and-navigation)
      - [Reinforcement Learning for Adaptive Decision-Making](#8-reinforcement-learning-for-adaptive-decision-making)
  - [Contributors](#contributors)
  
### System Requirements

- Ubuntu 24.04

- ROS 2 Jazzy

- Gazebo Harmonic

### Features

 #### 1. Camera-Based Image Acquisition and Recognition
   
   TIB is equipped with a high-definition camera capable of real-time environmental image acquisition, enabling object recognition and various vision-based functions.

   In the implementation, the relevant programs are located in `###`, and running the `### `script will start the camera image acquisition.
 
 #### 2. OpenCV and Deep Learning Integration
   
   Leveraging the OpenCV library for image processing, such as filtering and edge detection, combined with deep learning models to enhance the accuracy and robustness of object recognition.
 
 #### 3. LiDAR Data Acquisition and Visualization

   The LiDAR sensor captures 3D point cloud data of the environment, enabling the robot to perceive the distance and shape of surrounding objects.

 #### 4. Motion and Posture Data Acquisition and Display
  
   The Inertial Measurement Unit (IMU) collects motion state data such as acceleration and angular velocity, which is used for robot posture estimation.

 #### 5. Multisource Sensor Fusion Perception

   Data from the camera, LiDAR, IMU, and other sensors are fused to exploit the strengths of each modality, thereby improving the accuracy and reliability of environmental perception.

#### 6. Robotic Arm Manipulation Control
  
   TIB is equipped with a multi-degree-of-freedom robotic arm capable of grasping objects of various shapes and sizes, suitable for applications such as material handling and assembly.

#### 7. Autonomous Path Planning and Navigation

   TIB features autonomous navigation, allowing it to map the environment, plan optimal paths, avoid obstacles, and reach designated targets independently.

#### 8. Reinforcement Learning for Adaptive Decision-Making

   To enhance adaptability and decision-making in complex environments, the project integrates reinforcement learning techniques, enabling TIB to optimize its action strategies through continuous interaction with the environment.
 
### Contributors

We sincerely thank the following contributors to this project:

Chen Xu xuc@tju.edu.cn,
Yaru Wang:,
Xi Chen chenxi@tju.edu.cn, 
Xubo Yuan xbyuan@tju.edu.cn
Hongxiao Wu WHXwhx12305@163.com；Mingyi Li limingyi@bit.edu.cn；
Jiawei Li 18247395676@163.com.


   


