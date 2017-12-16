---
layout: post
title: "Learning Dense Facial Correspondences in Unconstrained Images"
date: 2017-09-02 06:02:26
categories: arXiv_CV
tags: arXiv_CV Sparse Face Tracking Detection Face_Detection
author: Ronald Yu, Shunsuke Saito, Haoxiang Li, Duygu Ceylan, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
We present a minimalistic but effective neural network that computes dense facial correspondences in highly unconstrained RGB images. Our network learns a per-pixel flow and a matchability mask between 2D input photographs of a person and the projection of a textured 3D face model. To train such a network, we generate a massive dataset of synthetic faces with dense labels using renderings of a morphable face model with variations in pose, expressions, lighting, and occlusions. We found that a training refinement using real photographs is required to drastically improve the ability to handle real images. When combined with a facial detection and 3D face fitting step, we show that our approach outperforms the state-of-the-art face alignment methods in terms of accuracy and speed. By directly estimating dense correspondences, we do not rely on the full visibility of sparse facial landmarks and are not limited to the model space of regression-based approaches. We also assess our method on video frames and demonstrate successful per-frame processing under extreme pose variations, occlusions, and lighting conditions. Compared to existing 3D facial tracking techniques, our fitting does not rely on previous frames or frontal facial initialization and is robust to imperfect face detections.

##### Abstract (translated by Google)
我们提出了一个简约而有效的神经网络，计算高度不受约束的RGB图像中的密集面部对应。我们的网络学习了一个人的二维输入照片和纹理三维人脸模型的投影之间的每像素流和一个匹配遮罩。为了训练这样一个网络，我们使用形态，表情，光线和遮挡的变化来形成具有密集标签的合成人脸的海量数据集。我们发现使用真实照片进行训练需要大幅提高处理真实图像的能力。结合面部检测和三维人脸拟合步骤，我们表明，我们的方法在准确性和速度方面胜过最先进的人脸对准方法。通过直接估计密集的对应关系，我们不依赖于稀疏面部标志的完全可见性，并不局限于基于回归的方法的模型空间。我们还评估我们的视频帧的方法，并演示在极端姿态变化，遮挡和光照条件下成功的每帧处理。与现有的3D面部跟踪技术相比，我们的拟合不依赖于之前的帧或正面面部初始化，并且对于不完美的面部检测是强健的。

##### URL
[https://arxiv.org/abs/1709.00536](https://arxiv.org/abs/1709.00536)

##### PDF
[https://arxiv.org/pdf/1709.00536](https://arxiv.org/pdf/1709.00536)

