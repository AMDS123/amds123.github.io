---
layout: post
title: "Encoderless Gimbal Calibration of Dynamic Multi-Camera Clusters"
date: 2018-07-24 18:45:52
categories: arXiv_CV
tags: arXiv_CV
author: Christopher L. Choi, Jason Rebello, Leonid Koppel, Pranav Ganti, Arun Das, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic Camera Clusters (DCCs) are multi-camera systems where one or more cameras are mounted on actuated mechanisms such as a gimbal. Existing methods for DCC calibration rely on joint angle measurements to resolve the time-varying transformation between the dynamic and static camera. This information is usually provided by motor encoders, however, joint angle measurements are not always readily available on off-the-shelf mechanisms. In this paper, we present an encoderless approach for DCC calibration which simultaneously estimates the kinematic parameters of the transformation chain as well as the unknown joint angles. We also demonstrate the integration of an encoderless gimbal mechanism with a state-of-the art VIO algorithm, and show the extensions required in order to perform simultaneous online estimation of the joint angles and vehicle localization state. The proposed calibration approach is validated both in simulation and on a physical DCC composed of a 2-DOF gimbal mounted on a UAV. Finally, we show the experimental results of the calibrated mechanism integrated into the OKVIS VIO package, and demonstrate successful online joint angle estimation while maintaining localization accuracy that is comparable to a standard static multi-camera configuration.

##### Abstract (translated by Google)
动态摄像机群集（DCC）是多摄像机系统，其中一个或多个摄像机安装在诸如万向节的致动机构上。用于DCC校准的现有方法依赖于关节角度测量来解决动态和静态相机之间的时变变换。这些信息通常由电机编码器提供，但是，现成的机制并不总能提供关节角度测量。在本文中，我们提出了一种用于DCC校准的无编码器方法，该方法同时估计变换链的运动学参数以及未知的关节角度。我们还展示了无编码万向节机构与最先进的VIO算法的集成，并展示了为了同时在线估计关节角度和车辆定位状态所需的扩展。所提出的校准方法在模拟和由安装在UAV上的2-DOF万向节组成的物理DCC上都得到验证。最后，我们展示了集成到OKVIS VIO软件包中的校准机制的实验结果，并展示了成功的在线关节角度估计，同时保持了与标准静态多摄像机配置相当的定位精度。

##### URL
[http://arxiv.org/abs/1807.09304](http://arxiv.org/abs/1807.09304)

##### PDF
[http://arxiv.org/pdf/1807.09304](http://arxiv.org/pdf/1807.09304)

