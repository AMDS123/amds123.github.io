---
layout: post
title: "Robust Performance-driven 3D Face Tracking in Long Range Depth Scenes"
date: 2015-07-10 04:52:36
categories: arXiv_CV
tags: arXiv_CV Face Tracking Optimization
author: Hai X. Pham, Chongyu Chen, Luc N. Dao, Vladimir Pavlovic, Jianfei Cai, Tat-jen Cham
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel robust hybrid 3D face tracking framework from RGBD video streams, which is capable of tracking head pose and facial actions without pre-calibration or intervention from a user. In particular, we emphasize on improving the tracking performance in instances where the tracked subject is at a large distance from the cameras, and the quality of point cloud deteriorates severely. This is accomplished by the combination of a flexible 3D shape regressor and the joint 2D+3D optimization on shape parameters. Our approach fits facial blendshapes to the point cloud of the human head, while being driven by an efficient and rapid 3D shape regressor trained on generic RGB datasets. As an on-line tracking system, the identity of the unknown user is adapted on-the-fly resulting in improved 3D model reconstruction and consequently better tracking performance. The result is a robust RGBD face tracker, capable of handling a wide range of target scene depths, beyond those that can be afforded by traditional depth or RGB face trackers. Lastly, since the blendshape is not able to accurately recover the real facial shape, we use the tracked 3D face model as a prior in a novel filtering process to further refine the depth map for use in other tasks, such as 3D reconstruction.

##### Abstract (translated by Google)
我们从RGBD视频流引入了一种新颖健壮的混合3D人脸跟踪框架，能够跟踪头部姿势和面部动作，而无需用户进行预先校准或干预。特别是在跟踪对象与摄像机距离较远的情况下，强调提高跟踪性能，使点云质量严重恶化。这是通过灵活的3D形状回归器和关于形状参数的联合2D + 3D优化的组合来实现的。我们的方法将面部混合形状与人体头部的点云进行匹配，同时由通用RGB数据集上训练的高效快速三维形状回归器驱动。作为一个在线跟踪系统，未知用户的身份被动态调整，从而改进了三维模型重建，从而实现了更好的跟踪性能。其结果是一个稳健的RGBD人脸追踪器，能够处理范围广泛的目标场景深度，超出了传统深度或RGB面部追踪器所能提供的深度。最后，由于混合形状不能准确恢复真实的面部形状，我们使用跟踪的三维人脸模型作为一种新的过滤过程中的先验，以进一步细化深度图用于其他任务，如三维重建。

##### URL
[https://arxiv.org/abs/1507.02779](https://arxiv.org/abs/1507.02779)

##### PDF
[https://arxiv.org/pdf/1507.02779](https://arxiv.org/pdf/1507.02779)

