---
layout: post
title: "Dense Human Body Correspondences Using Convolutional Networks"
date: 2016-06-26 01:06:43
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Deep_Learning
author: Lingyu Wei, Qixing Huang, Duygu Ceylan, Etienne Vouga, Hao Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep learning approach for finding dense correspondences between 3D scans of people. Our method requires only partial geometric information in the form of two depth maps or partial reconstructed surfaces, works for humans in arbitrary poses and wearing any clothing, does not require the two people to be scanned from similar viewpoints, and runs in real time. We use a deep convolutional neural network to train a feature descriptor on depth map pixels, but crucially, rather than training the network to solve the shape correspondence problem directly, we train it to solve a body region classification problem, modified to increase the smoothness of the learned descriptors near region boundaries. This approach ensures that nearby points on the human body are nearby in feature space, and vice versa, rendering the feature descriptor suitable for computing dense correspondences between the scans. We validate our method on real and synthetic data for both clothed and unclothed humans, and show that our correspondences are more robust than is possible with state-of-the-art unsupervised methods, and more accurate than those found using methods that require full watertight 3D geometry.

##### Abstract (translated by Google)
我们提出一个深入的学习方法，以找出3D扫描的人之间密集的对应关系。我们的方法只需要以两个深度图或部分重建表面的形式的部分几何信息，为任意姿势的人类穿着任何服装，并不要求两个人从类似的观点扫描，并实时运行。我们使用深度卷积神经网络来训练深度图像素上的特征描述符，但关键的是，而不是直接训练网络来解决形状对应问题，我们训练它来解决身体区域分类问题，修改以增加平滑度学习到的区域边界附近的描述符。这种方法确保人体附近的点在特征空间附近，反之亦然，使得特征描述符适合于计算扫描之间的密集对应。我们验证了我们的方法在真实和合成的数据上都穿上衣服和不穿衣服的人，并表明我们的通信比最先进的无监督方法更可靠，比使用需要完全防水的方法更为准确3D几何。

##### URL
[https://arxiv.org/abs/1511.05904](https://arxiv.org/abs/1511.05904)

##### PDF
[https://arxiv.org/pdf/1511.05904](https://arxiv.org/pdf/1511.05904)

