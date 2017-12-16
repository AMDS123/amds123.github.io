---
layout: post
title: "DART: Distribution Aware Retinal Transform for Event-based Cameras"
date: 2017-10-30 08:08:57
categories: arXiv_CV
tags: arXiv_CV Face Tracking Object_Tracking Classification Recognition
author: Bharath Ramesh, Hong Yang, Garrick Orchard, Ngoc Anh Le Thi, Cheng Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new event-based visual descriptor, termed as distribution aware retinal transform (DART), for pattern recognition using silicon retina cameras. The DART descriptor captures the information of the spatio-temporal distribution of events, and forms a rich structural representation. Consequently, the event context encoded by DART greatly simplifies the feature correspondence problem, which is highly relevant to many event-based vision problems. The proposed descriptor is robust to scale and rotation variations without the need for spectral analysis. To demonstrate the effectiveness of the DART descriptors, they are employed as local features in the bag-of-features classification framework. The proposed framework is tested on the N-MNIST, MNIST-DVS, CIFAR10-DVS, NCaltech-101 datasets, as well as a new object dataset, N-SOD (Neuromorphic-Single Object Dataset), collected to test unconstrained viewpoint recognition. We report a competitive classification accuracy of 97.95% on the N-MNIST and the best classification accuracy compared to existing works on the MNIST-DVS (99%), CIFAR10-DVS (65.9%) and NCaltech-101 (70.3%). Using the in-house N-SOD, we demonstrate real-time classification performance on an Intel Compute Stick directly interfaced to an event camera flying on-board a quadcopter. In addition, taking advantage of the high-temporal resolution of event cameras, the classification system is extended to tackle object tracking. Finally, we demonstrate efficient feature matching for event-based cameras using kd-trees.

##### Abstract (translated by Google)
我们引入了一种新的基于事件的视觉描述符，称为分布感知视网膜变换（DART），用于使用硅视网膜相机进行模式识别。 DART描述符捕获事件的时空分布信息，并形成丰富的结构表示。因此，由DART编码的事件上下文极大地简化了与许多基于事件的视觉问题高度相关的特征对应问题。所提出的描述符在不需要频谱分析的情况下对比例和旋转变化是鲁棒的。为了演示DART描述符的有效性，它们被用作特征分类框架中的局部特征。在N-MNIST，MNIST-DVS，CIFAR10-DVS，NCaltech-101数据集以及一个新的对象数据集N-SOD（神经形态单个对象数据集）上测试了所提出的框架，以测试无约束的视点识别。与MNIST-DVS（99％），CIFAR10-DVS（65.9％）和NCaltech-101（70.3％）的现有作品相比，我们报告N-MNIST的竞争分类准确率为97.95％，分类准确率最高。使用内部的N-SOD，我们演示了直接连接到四轴飞行器上的事件摄像头的英特尔计算棒上的实时分类性能。此外，利用事件相机的高时间分辨率，分类系统被扩展到解决对象跟踪。最后，我们演示了使用kd-trees的基于事件的相机的高效特征匹配。

##### URL
[https://arxiv.org/abs/1710.10800](https://arxiv.org/abs/1710.10800)

##### PDF
[https://arxiv.org/pdf/1710.10800](https://arxiv.org/pdf/1710.10800)

