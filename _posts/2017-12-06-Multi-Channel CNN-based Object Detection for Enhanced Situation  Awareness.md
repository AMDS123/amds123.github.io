---
layout: post
title: 'Multi-Channel CNN-based Object Detection for Enhanced Situation  Awareness'
date: 2017-12-06 01:34:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Shuo Liu, Zheng Liu
---

* content
{:toc}

##### Abstract
Object Detection is critical for automatic military operations. However, the performance of current object detection algorithms is deficient in terms of the requirements in military scenarios. This is mainly because the object presence is hard to detect due to the indistinguishable appearance and dramatic changes of object's size which is determined by the distance to the detection sensors. Recent advances in deep learning have achieved promising results in many challenging tasks. The state-of-the-art in object detection is represented by convolutional neural networks (CNNs), such as the fast R-CNN algorithm. These CNN-based methods improve the detection performance significantly on several public generic object detection datasets. However, their performance on detecting small objects or undistinguishable objects in visible spectrum images is still insufficient. In this study, we propose a novel detection algorithm for military objects by fusing multi-channel CNNs. We combine spatial, temporal and thermal information by generating a three-channel image, and they will be fused as CNN feature maps in an unsupervised manner. The backbone of our object detection framework is from the fast R-CNN algorithm, and we utilize cross-domain transfer learning technique to fine-tune the CNN model on generated multi-channel images. In the experiments, we validated the proposed method with the images from SENSIAC (Military Sensing Information Analysis Centre) database and compared it with the state-of-the-art. The experimental results demonstrated the effectiveness of the proposed method on both accuracy and computational efficiency.

##### Abstract (translated by Google)
对象检测对自动军事行动至关重要。然而，目前的目标检测算法的性能在军事情况下的要求是不足的。这主要是因为由于与探测传感器的距离所决定的物体尺寸的显着变化和难以区分的物体的存在难以被检测到。深度学习的最新进展在许多具有挑战性的任务中取得了可喜的成果目标检测的最新技术由卷积神经网络（CNN）表示，例如快速R-CNN算法。这些基于CNN的方法显着提高了几个公共通用对象检测数据集的检测性能。然而，它们在检测可见光谱图像中的小物体或不可区分的物体方面的性能仍然不足。在这项研究中，我们提出了一种融合多通道CNN的军事目标检测算法。我们通过生成三通道图像来组合空间信息，时间信息和热信息，并将它们以无监督的方式融合为CNN特征地图。我们的目标检测框架的骨干来自快速R-CNN算法，我们利用跨域传输学习技术来对生成的多通道图像上的CNN模型进行微调。在实验中，我们用SENSIAC（军事传感信息分析中心）数据库中的图像验证了所提出的方法，并将其与现有技术相比较。实验结果证明了该方法在精度和计算效率上的有效性。

##### URL
[https://arxiv.org/abs/1712.00075](https://arxiv.org/abs/1712.00075)

