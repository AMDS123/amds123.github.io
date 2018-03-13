---
layout: post
title: "A Deep Learning Approach for Pose Estimation from Volumetric OCT Data"
date: 2018-03-10 18:48:18
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking CNN Deep_Learning Quantitative
author: Nils Gessert, Matthias Schlüter, Alexander Schlaefer
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking the pose of instruments is a central problem in image-guided surgery. For microscopic scenarios, optical coherence tomography (OCT) is increasingly used as an imaging modality. OCT is suitable for accurate pose estimation due to its micrometer range resolution and volumetric field of view. However, OCT image processing is challenging due to speckle noise and reflection artifacts in addition to the images' 3D nature. We address pose estimation from OCT volume data with a new deep learning-based tracking framework. For this purpose, we design a new 3D convolutional neural network (CNN) architecture to directly predict the 6D pose of a small marker geometry from OCT volumes. We use a hexapod robot to automatically acquire labeled data points which we use to train 3D CNN architectures for multi-output regression. We use this setup to provide an in-depth analysis on deep learning-based pose estimation from volumes. Specifically, we demonstrate that exploiting volume information for pose estimation yields higher accuracy than relying on 2D representations with depth information. Supporting this observation, we provide quantitative and qualitative results that 3D CNNs effectively exploit the depth structure of marker objects. Regarding the deep learning aspect, we present efficient design principles for 3D CNNs, making use of insights from the 2D deep learning community. In particular, we present Inception3D as a new architecture which performs best for our application. We show that our deep learning approach reaches errors at our ground-truth label's resolution. We achieve a mean average error of $\SI{14.89 \pm 9.3}{\micro\metre}$ and $\SI{0.096 \pm 0.072}{\degree}$ for position and orientation learning, respectively.

##### Abstract (translated by Google)
跟踪仪器的姿势是图像引导手术的核心问题。对于微观情况，光学相干断层扫描（OCT）越来越多地用作成像模式。由于其微米范围分辨率和体积视场，OCT适用于精确的姿态估计。但是，除了图像的3D特性之外，由于斑点噪声和反射伪影，OCT图像处理具有挑战性。我们用一个新的基于深度学习的追踪框架来解决OCT体数据中的姿态估计问题。为此，我们设计了一种新的三维卷积神经网络（CNN）体系结构，以直接预测OCT体积中小标记几何体的6D姿态。我们使用六足机器人自动获取标记的数据点，我们用它来训练3D CNN架构以进行多输出回归。我们使用这种设置来深入分析基于体积的深度学习姿势估计。具体而言，我们证明，利用体积信息进行姿态估计的结果比依靠具有深度信息的2D表示更精确。支持这一观察，我们提供了定量和定性的结果，3D CNNs有效地利用标记对象的深度结构。关于深度学习方面，我们提出了3D CNN的高效设计原则，利用2D深度学习社区的见解。具体而言，我们将Inception3D作为一个新的架构呈现，它对我们的应用程序表现最佳。我们表明，我们的深度学习方法在我们的地面实况标签的解决方案中达到了错误。对于位置和方向学习，我们分别获得了$ \ SI {14.89 \ pm 9.3} {\ micro \ meter} $和$ \ SI {0.096 \ pm 0.072} {\ degree} $的均值平均误差。

##### URL
[https://arxiv.org/abs/1803.03852](https://arxiv.org/abs/1803.03852)

##### PDF
[https://arxiv.org/pdf/1803.03852](https://arxiv.org/pdf/1803.03852)

