---
layout: post
title: "Fused DNN: A deep neural network fusion approach to fast and robust pedestrian detection"
date: 2017-05-28 15:45:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Xianzhi Du, Mostafa El-Khamy, Jungwon Lee, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep neural network fusion architecture for fast and robust pedestrian detection. The proposed network fusion architecture allows for parallel processing of multiple networks for speed. A single shot deep convolutional network is trained as a object detector to generate all possible pedestrian candidates of different sizes and occlusions. This network outputs a large variety of pedestrian candidates to cover the majority of ground-truth pedestrians while also introducing a large number of false positives. Next, multiple deep neural networks are used in parallel for further refinement of these pedestrian candidates. We introduce a soft-rejection based network fusion method to fuse the soft metrics from all networks together to generate the final confidence scores. Our method performs better than existing state-of-the-arts, especially when detecting small-size and occluded pedestrians. Furthermore, we propose a method for integrating pixel-wise semantic segmentation network into the network fusion architecture as a reinforcement to the pedestrian detector. The approach outperforms state-of-the-art methods on most protocols on Caltech Pedestrian dataset, with significant boosts on several protocols. It is also faster than all other methods.

##### Abstract (translated by Google)
我们提出了一种深度神经网络融合架构，用于快速和健壮的行人检测。所提出的网络融合体系结构允许为了速度而并行处理多个网络。一次性深度卷积网络被训练成一个物体检测器来生成所有可能的不同大小和遮挡的行人候选。这个网络输出了大量的行人候选人来覆盖大多数的地面真实行人，同时也引入了大量的误报。接下来，并行使用多个深度神经网络来进一步细化这些行人候选者。我们引入一种基于软排斥的网络融合方法，将来自所有网络的软指标融合在一起，以产生最终的置信度分数。我们的方法比现有技术的表现要好，特别是在检测小型行人和封闭式行人时。此外，我们提出了一种将像素级语义分割网络融合到网络融合结构中作为行人检测器的增强的方法。该方法优于加州理工学院行人数据集上大多数协议的最先进的方法，对几种协议有显着提升。它比所有其他方法都快。

##### URL
[https://arxiv.org/abs/1610.03466](https://arxiv.org/abs/1610.03466)

##### PDF
[https://arxiv.org/pdf/1610.03466](https://arxiv.org/pdf/1610.03466)

