# SLAM @ HKU-MaRS
# 1. Introduction
## 1.1 Introduction to HKU-MaRS lab
Welcome to the Mechatronics and Robotic Systems (MaRS) Laboratory, located in the Department of Mechanical Engineering at the prestigious University of Hong Kong (HKU). Our mission is to push the boundaries of mechatronic systems and robotics, by emphasizing practical applications that can improve human life and industry.

At MaRS Lab, our current research focuses on the design, planning, and control of aerial robots, as well as lidar-based simultaneous localization and mapping (SLAM). We believe that these technologies can have a significant impact on many fields, from search and rescue operations to agriculture and beyond.

## 1.2 Introduction to this repository
In this GitHub repository, we **present our latest research works related to SLAM**, organized chronologically by their ***publication date***. These works showcase our team's innovative ideas, rigorous methodologies, and cutting-edge solutions in the field of robotics. We hope that our work inspires you, and we welcome collaboration and feedback from the robotics community.

## 1.3 Contributors (organized by letter A-Z)
- Fu Zhang (Supervisor) 张富(导师)
- [Chonjiang Yuan 袁崇健](https://github.com/ChongjianYUAN)
- Chunrang Zheng 郑纯然
- Dongjiao He 贺东娇
- [Fangcheng Zhu 朱方程](https://github.com/zfc-zfc)
- [Jiarong Lin 林家荣](https://jiaronglin.com/)
- Wei Xu 徐威
- Xiyuan Liu 刘晰源
- [Yixi Cai 蔡逸熙](https://github.com/Ecstasy-EC)
- Zheng Liu 刘政

## 1.4 Acknowledgement (TODO)
Todo

## 1.5 Relative Talks and seminars
- [【深蓝学院】基于多传感器融合的定位和建图系统](https://www.shenlanxueyuan.com/open/course/181)
  - [PPT: Simultaneous_localization_and_mapping_with_Multi-sensor_Fusion.pdf](https://jiaronglin.com/uploads/Simultaneous_localization_and_mapping_with_Multi-sensor_Fusion.pdf)

# 2. SLAM researches @ HKU-MaRS
### Loam_livox: A fast, robust, high-precision LiDAR odometry and mapping package for LiDARs of small FoV 
- Author: [Jiarong Lin](https://jiaronglin.com/), Fu Zhang
- Date: 2020/05
- Accepted to **ICRA2020**
- Github (★1.2k): https://github.com/hku-mars/loam_livox
- Category: LiDAR SLAM
- Relative notes & articles:
  - [【泡泡图灵智库】Loam livox：一种用于小视场角激光雷达的快速、鲁棒、高精度的激光雷达里程计和建图包](https://mp.weixin.qq.com/s/Ym5g0xf8Dlqet20x80WaZQ)
  - [如何评价大疆投资的激光雷达在国内正式开售？会有哪些影响？ - ziv.lin的回答 - 知乎](
https://www.zhihu.com/question/332926945/answer/836032023)
  - [激光SLAM | 基于固态雷达的里程计：Loam Livox - 任乾的文章 - 知乎](https://zhuanlan.zhihu.com/p/93579424)


### A decentralized framework for simultaneous calibration, localization and mapping with multiple LiDARs
- Author: [Jiarong Lin](https://jiaronglin.com/), Xiyuan Liu, Fu Zhang
- Date: 2020/10
- Accepted to **IROS2020** 
- Github (★171): https://github.com/hku-mars/decentralized_loam
- Category: LiDAR SLAM; Multi-LiDAR fusion
- Relative notes & articles:
  - [多激光雷达的协同定位建图及在线外参自标定 - ziv.lin的文章 - 知乎](https://zhuanlan.zhihu.com/p/157533731)

### ikd-Tree: An Incremental K-D Tree for Robotic Applications
- Author: Yixi Cai, Wei Xu, Fu Zhang
- Date: 2021/02
- Github (★415): https://github.com/hku-mars/ikd-Tree
- Category: LiDAR SLAM, Map Structure
- Relative notes & articles:
  - [数据结构专题(二) | ikd-Tree: 港大开源增量式 kd-tree 结构 & 开源中文注释](https://zhuanlan.zhihu.com/p/529926254)

### Balm: Bundle adjustment for lidar mapping
- Author: Zheng Liu, Fu Zhang
- Date: 2021/03
- Accepted to **RA-L2021**
- Github (★436): https://github.com/hku-mars/BALM
- Category: LiDAR Bundle adjustment

### Fast-lio: A fast, robust lidar-inertial odometry package by tightly-coupled iterated kalman filter
- Author: Wei Xu, Fu Zhang
- Date: 2021/03
- Accepted to **RA-L2021**
- Github (★1.4K): https://github.com/hku-mars/FAST_LIO
- Category: LiDAR SLAM; LiDAR-Inertial fusion
- Relative notes & articles:
  - [【泡泡图灵智库】FAST-LIO: 基于迭代卡尔曼的激光惯性里程计软件包](https://mp.weixin.qq.com/s/WsplEpdh-c_Rjz9fCOF9Ig) 
  - [【点云时空LOAM专题】Fast-LIO & Fast-LIO2 原理及代码解析](https://mp.weixin.qq.com/s/x7dG9fxoSwejaWc4aEAQFw)

### Extrinsic Calibration of Multiple LiDARs of Small FoV in Targetless Environments
- Author: Xiyuan Liu, Fu Zhang
- Date: 2021/04
- Accepted to **RA-L2021**
- Category: LiDAR-LiDAR calibration

### R<sup>2</sup>LIVE: A Robust, Real-Time, LiDAR-Inertial-Visual Tightly-Coupled State Estimator and Mapping
- Author: [Jiarong Lin](https://jiaronglin.com/), Chunran Zheng, Wei Xu, Fu Zhang
- Date: 2021/07
- Accepted to **RA-L2021**
- Github (★622): https://github.com/hku-mars/r2live
- Category: LiDAR SLAM; LiDAR-Inertial-Visual fusion
- Relative notes & articles:
  - [【泡泡图灵智库】R2LIVE: 一个鲁棒实时的雷达-惯导-视觉紧耦合的位姿估计和建图系统](https://mp.weixin.qq.com/s/W60TtqD3Dikx2NGER0d_gA)
  - [【泡泡点云时空】R2LIVE：鲁棒，实时，雷达-IMU-视觉紧耦合状态估计及建图](https://mp.weixin.qq.com/s/sdiuZlApr-aP0B5J12hQ_A)
  - [论文阅读《R2LIVE: A Robust, Real-time, LiDAR-Inertial-Visual tightly-coupled state Estimator and mapping》 - 晃晃悠悠的虚无周的文章 - 知乎](https://zhuanlan.zhihu.com/p/377319191)

### Pixel-level extrinsic self calibration of high resolution lidar and camera in targetless environments
- Author: Chongjian Yuan, Xiyuan Liu, Xiaoping Hong, Fu Zhang
- Date: 2021/07
- Accepted to **RA-L2021**
- Github (★549): https://github.com/hku-mars/livox_camera_calib
- Category: LiDAR-Camera calibration
- Relative notes & articles:
  - [【泡泡点云时空】像素精度的高分辨率雷达和相机外参自标定](https://mp.weixin.qq.com/s/UYuOmoWi96RuRXr-VqJwuA)

### Fast-lio2: Fast direct lidar-inertial odometry
- Author: Wei Xu, Yixi Cai, Dongjiao He, [Jiarong Lin](https://jiaronglin.com/), Fu Zhang
- Date: 2021/07
- Accepted to **T-RO2022**
- Github (★1.4K): https://github.com/hku-mars/FAST_LIO
- Category: LiDAR SLAM; LiDAR-Inertial fusion
- Relative notes & articles:
  - [【泡泡图灵智库】FAST-LIO2: 快速且直接的激光雷达与惯导里程计](https://mp.weixin.qq.com/s/VFByGE3fXtXos5Mx1vB7cA) 
  - [【点云时空LOAM专题】Fast-LIO & Fast-LIO2 原理及代码解析](https://mp.weixin.qq.com/s/x7dG9fxoSwejaWc4aEAQFw)

### R<sup>3</sup>LIVE: A Robust, Real-time, RGB-colored, LiDAR-Inertial-Visual tightly-coupled state Estimation and mapping package
- Author: [Jiarong Lin](https://jiaronglin.com/), Fu Zhang
- Date: 2021/09
- Accepted to **ICRA2022**
- Github (★1.4K): https://github.com/hku-mars/r3live
- Category: LiDAR SLAM; LiDAR-Inertial-Visual fusion
- Relative notes & articles:
  - [【泡泡图灵智库】R3LIVE：一个实时鲁棒、且有RGB着色的激光雷达-惯性-视觉紧耦合系统](https://mp.weixin.qq.com/s/tMC46tlIcPPMXhkiSp2ogw)
  - [Livox 学术先锋 ｜ 香港大学 MaRS 实验室 R3LIVE 实时鲁棒性紧耦合系统](https://www.livoxtech.com/cn/showcase/livox-r3live)
  - [R3LIVE开源代码全体验及测试 - 颍川滞的文章 - 知乎](https://zhuanlan.zhihu.com/p/453038352)
  - [论文阅读 R3LIVE: A Robust, Real-time, RGB-colored, LiDAR-Inertial-Visual tightly-coupled state ... - 晃晃悠悠的虚无周的文章 - 知乎](https://zhuanlan.zhihu.com/p/428827372)
  - [R3LIVE 代码解析 - stella的文章 - 知乎](https://zhuanlan.zhihu.com/p/480275319)

### Robust real-time lidar-inertial initialization
- Author: Fangcheng Zhu, Yunfan Ren, Fu Zhang
- Date: 2022/02
- Accepted to **IROS2022**
- Github (★401): https://github.com/hku-mars/LiDAR_IMU_Init
- Category: LiDAR-IMU calibration
- Relative Notes & Articles
 [论文解读 Robust Real-time LiDAR-inertial Initialization (IROS2022)](https://zhuanlan.zhihu.com/p/643584117)

### FAST-LIVO: Fast and Tightly-coupled Sparse-Direct LiDAR-Inertial-Visual Odometry
- Author: Chunran Zheng, Qingyan Zhu, Wei Xu, Xiyuan Liu, Qizhi Guo, Fu Zhang
- Date: 2022/03
- Accepted to **IROS2022**
- Github (★533): https://github.com/hku-mars/FAST-LIVO
- Category: LiDAR SLAM; LiDAR-Inertial-Visual fusion
- Relative notes & articles:
  - [【泡泡点云时空】FAST-LIVO: 快速且紧耦合的稀疏直接LiDAR-惯性-视觉里程计](https://mp.weixin.qq.com/s/xpwDxFHNqHaergU1GA9uXA)

### Targetless extrinsic calibration of multiple small FoV LiDARs and cameras using adaptive voxelization
- Author: Xiyuan Liu, Chongjian Yuan, Fu Zhang
- Date: 2022/05
- Accepted to **TIM2022**
- Github (★278): https://github.com/hku-mars/mlcc
- Category: LiDAR-LiDAR & LiDAR-Camera calibration

### Efficient and probabilistic adaptive voxel mapping for accurate online lidar odometry
- Author: Chongjian Yuan, Wei Xu, Xiyuan Liu, Xiaoping Hong, Fu Zhang
- Date: 2022/07
- Accepted to **RA-L2022**
- Github (★274): https://github.com/hku-mars/VoxelMap
- Category: LiDAR SLAM
- Relative notes & articles:
  - [【泡泡点云时空】高效和概率自适应体素建图实现的精确在线雷达里程计](https://mp.weixin.qq.com/s/idOkmf7l29xw7RQHr3OyZQ)

### R<sup>3</sup>LIVE++: A Robust, Real-time, Radiance reconstruction package with a tightly-coupled LiDAR-Inertial-Visual state Estimator
- Author: [Jiarong Lin](https://jiaronglin.com/), Fu Zhang
- Date: 2022/09
- Under review
- Github (★1.4K): https://github.com/hku-mars/r3live
- Category: LiDAR SLAM; LiDAR-Inertial-Visual fusion
- Relative notes & articles:
  - [多传感器融合SLAM|R3LIVE++论文带读（一）- 自动驾驶专栏的文章 - 知乎](https://zhuanlan.zhihu.com/p/596228149)
  - [多传感器融合SLAM|R3LIVE++论文带读（二）- 自动驾驶专栏的文章 - 知乎](https://zhuanlan.zhihu.com/p/596957937)
  - [多传感器融合SLAM|R3LIVE++论文带读（三）- 自动驾驶专栏的文章 - 知乎](https://zhuanlan.zhihu.com/p/598236929)
  - [多传感器融合SLAM|R3LIVE++论文带读（四）- 自动驾驶专栏的文章 - 知乎](https://zhuanlan.zhihu.com/p/598276346)
  - [R3LIVE++：一个鲁棒实时的重建package！具有紧密耦合的激光雷达惯性视觉状态估计器 - 自动驾驶之心的文章 - 知乎](https://zhuanlan.zhihu.com/p/568436911)

### STD: Stable Triangle Descriptor for 3D place recognition
- Author: Chongjian Yuan*, [Jiarong Lin](https://jiaronglin.com/)*, Zuhao Zou, Xiaoping Hong, Fu Zhang
- Date: 2022/09
- Accepted to **ICRA2023**
- Github (★197): https://github.com/hku-mars/STD
- Category: loop detection & closure

### Decentralized LiDAR-inertial Swarm Odometry
- Author: Fangcheng Zhu, Yunfan Ren, Fanze Kong, Huajie Wu, Siqi Liang, Nan Chen, Wei Xu, Fu Zhang
- Date: 2022/09
- Accepted to **ICRA2023** 
- Category: LiDAR SLAM; Multi-LiDAR fusion

### Large-Scale LiDAR Consistent Mapping using Hierachical LiDAR Bundle Adjustment
- Author: Xiyuan Liu, Zheng Liu, Fanze Kong, Fu Zhang
- Date: 2023/03
- Accepted to **RA-L2023**
- Category: LiDAR Bundle Adjustment

### Efficient and Consistent Bundle Adjustment on Lidar Point Clouds
- Author: Zheng Liu, Xiyuan Liu, Fu Zhang
- Date: 2022/09
- Under review
- Github (★436): https://github.com/hku-mars/BALM
- Category: LiDAR Bundle Adjustment

### Symbolic Representation and Toolkit Development of Iterated Error-State Extended Kalman Filters on Manifolds
- Author: Dongjiao He, Wei Xu, Fu Zhang
- Date: 2023/01
- Accepted to **TIE2023**
- Github (★248): https://github.com/hku-mars/IKFoM
- Category: LiDAR SLAM

### ImMesh: An Immediate LiDAR Localization and Meshing Framework
- Author: [Jiarong Lin*](https://jiaronglin.com/), Chongjiang Yuan*, Yixi Cai, Haotian Li, Yuying Zou, Xiaoping Hong, Fu Zhang
- Date: 2023/01
- Under review
- Github (★277): https://github.com/hku-mars/ImMesh
- Category: LiDAR SLAM

### Point-LIO: Robust High-Bandwidth Lidar-Inertial Odometry
- Author: Dongjiao He, Wei Xu, Nan Chen, Fanze Kong, Chongjian Yuan, Fu Zhang
- Date: 2023/03
- Accepted to **AIS2023**
- Github (★278): https://github.com/hku-mars/Point-LIO
- Category: LiDAR SLAM; LiDAR-Inertial fusion
