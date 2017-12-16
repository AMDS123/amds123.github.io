---
layout: post
title: "PoseCNN: A Convolutional Neural Network for 6D Object Pose Estimation in Cluttered Scenes"
date: 2017-11-01 04:10:58
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Yu Xiang, Tanner Schmidt, Venkatraman Narayanan, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the 6D pose of known objects is important for robots to interact with objects in the real world. The problem is challenging due to the variety of objects as well as the complexity of the scene caused by clutter and occlusion between objects. In this work, we introduce a new Convolutional Neural Network (CNN) for 6D object pose estimation named PoseCNN. PoseCNN estimates the 3D translation of an object by localizing its center in the image and predicting its distance from the camera. The 3D rotation of the object is estimated by regressing to a quaternion representation. PoseCNN is able to handle symmetric objects and is also robust to occlusion between objects. In addition, we contribute a large scale video dataset for 6D object pose estimation named the YCB-Video dataset. Our dataset provides accurate 6D poses of 21 objects from the YCB dataset observed in 92 videos with 133,827 frames. We conduct experiments on our YCB-Video dataset and the OccludedLINEMOD dataset to show that PoseCNN provides very good estimates using only color as input.

##### Abstract (translated by Google)
估算已知物体的6D姿态对机器人与现实世界中的物体进行交互非常重要。由于物体的多样性以及由物体之间的杂乱和遮挡引起的场景的复杂性，这个问题是具有挑战性的。在这项工作中，我们引入了一种新的用于6D目标姿态估计的卷积神经网络（CNN），名为PoseCNN。 PoseCNN通过在图像中定位其中心并预测其与相机的距离来估计物体的3D平移。对象的3D旋转通过回归到四元数表示来估计。 PoseCNN能够处理对称对象，并且对于对象之间的遮挡也是强健的。此外，我们还提供了一个名为YCB-Video数据集的6D对象姿态估计的大型视频数据集。我们的数据集提供了来自YCB数据集的21个对象的精确6D姿态，在92个视频中观察到133,827帧。我们在YCB-Video数据集和OccludedLINEMOD数据集上进行实验，以显示PoseCNN仅使用颜色作为输入提供了非常好的估计。

##### URL
[https://arxiv.org/abs/1711.00199](https://arxiv.org/abs/1711.00199)

##### PDF
[https://arxiv.org/pdf/1711.00199](https://arxiv.org/pdf/1711.00199)

