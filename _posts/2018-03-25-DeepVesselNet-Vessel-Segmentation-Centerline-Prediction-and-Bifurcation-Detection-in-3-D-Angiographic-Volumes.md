---
layout: post
title: "DeepVesselNet: Vessel Segmentation, Centerline Prediction, and Bifurcation Detection in 3-D Angiographic Volumes"
date: 2018-03-25 21:09:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning Deep_Learning Prediction Detection
author: Giles Tetteh, Velizar Efremov, Nils D. Forkert, Matthias Schneider, Jan Kirschke, Bruno Weber, Claus Zimmer, Marie Piraud, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
We present DeepVesselNet, an architecture tailored to the challenges to be addressed when extracting vessel networks and corresponding features in 3-D angiography using deep learning. We discuss the problems of low execution speed and high memory requirements associated with full 3-D convolutional networks, high class imbalance arising from low percentage (less than 3%) of vessel voxels, and unavailability of accurately annotated training data - and offer solutions that are the building blocks of DeepVesselNet. First, we formulate 2-D orthogonal cross-hair filters which make use of 3-D context information. Second, we introduce a class balancing cross-entropy score with false positive rate correction to handle the high class imbalance and high false positive rate problems associated with existing loss functions. Finally, we generate synthetic dataset using a computational angiogenesis model, capable of generating vascular networks under physiological constraints on local network structure and topology, and use these data for transfer learning. DeepVesselNet is optimized for segmenting vessels, predicting centerlines, and localizing bifurcations. We test the performance on a range of angiographic volumes including clinical Time-of-Flight MRA data of the human brain, as well as synchrotron radiation X-ray tomographic microscopy scans of the rat brain. Our experiments show that, by replacing 3-D filters with 2-D orthogonal cross-hair filters in our network, speed is improved by 23% while accuracy is maintained. Our class balancing metric is crucial for training the network and pre-training with synthetic data helps in early convergence of the training process.

##### Abstract (translated by Google)
我们提供了DeepVesselNet，这是一种适合在使用深度学习提取血管网络和三维血管造影相应特征时要解决的挑战的体系结构。我们讨论与全三维卷积网络相关的低执行速度和高内存要求，由于血管体素百分比低（不到3％）导致的高级别不平衡以及无法准确注释训练数据等问题，并提供解决方案是DeepVesselNet的基石。首先，我们制定了利用三维上下文信息的二维正交交叉滤波器。其次，我们引入了具有误报率校正的班级平衡交叉熵分数来处理与现有损失函数相关的高级失衡和高误报率问题。最后，我们使用计算血管生成模型生成合成数据集，能够在局部网络结构和拓扑的生理约束下生成血管网络，并将这些数据用于转移学习。 DeepVesselNet针对船舶分段，预测中心线和本地化分叉进行了优化。我们测试了一系列血管造影量的表现，包括人脑的临床飞行时间MRA数据以及大鼠脑的同步辐射X射线断层扫描显微镜扫描。我们的实验表明，通过在我们的网络中用2-D正交交叉滤波器代替3-D滤波器，在保持精度的同时，速度提高了23％。我们的班级平衡度量对于训练网络至关重要，并且使用综合数据进行预训练有助于训练过程的早期融合。

##### URL
[https://arxiv.org/abs/1803.09340](https://arxiv.org/abs/1803.09340)

##### PDF
[https://arxiv.org/pdf/1803.09340](https://arxiv.org/pdf/1803.09340)

