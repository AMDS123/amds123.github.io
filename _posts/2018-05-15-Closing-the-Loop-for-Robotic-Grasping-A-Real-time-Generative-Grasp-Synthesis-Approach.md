---
layout: post
title: "Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach"
date: 2018-05-15 08:27:32
categories: arXiv_RO
tags: arXiv_RO Adversarial CNN
author: Douglas Morrison, Peter Corke, J&#xfc;rgen Leitner
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a real-time, object-independent grasp synthesis method which can be used for closed-loop grasping. Our proposed Generative Grasping Convolutional Neural Network (GG-CNN) predicts the quality and pose of grasps at every pixel. This one-to-one mapping from a depth image overcomes limitations of current deep-learning grasping techniques by avoiding discrete sampling of grasp candidates and long computation times. Additionally, our GG-CNN is orders of magnitude smaller while detecting stable grasps with equivalent performance to current state-of-the-art techniques. The light-weight and single-pass generative nature of our GG-CNN allows for closed-loop control at up to 50Hz, enabling accurate grasping in non-static environments where objects move and in the presence of robot control inaccuracies. In our real-world tests, we achieve an 83% grasp success rate on a set of previously unseen objects with adversarial geometry and 88% on a set of household objects that are moved during the grasp attempt. We also achieve 81% accuracy when grasping in dynamic clutter.

##### Abstract (translated by Google)
本文提出了一种实时的，与对象无关的抓取合成方法，可用于闭环抓取。我们提出的生成式抓取卷积神经网络（GG-CNN）预测每个像素处的抓取质量和姿态。这种来自深度图像的一对一映射克服了当前深度学习抓取技术的局限性，其避免了对候选抓取的离散采样和长计算时间。此外，我们的GG-CNN在检测稳定的抓握时与目前最先进的技术具有相同的性能，数量级更小。我们的GG-CNN的轻量化和单通道生成特性允许在高达50Hz的频率下进行闭环控制，从而在物体移动的非静态环境中以及机器人控制不准确的情况下实现精确抓取。在我们的实际测试中，我们对一组以前看不见的物体拥有敌对几何体的抓握成功率为83％，对抓握尝试期间移动的一组家庭物体的抓握成功率为88％。抓住动态杂波时，我们也能达到81％的准确度。

##### URL
[http://arxiv.org/abs/1804.05172](http://arxiv.org/abs/1804.05172)

##### PDF
[http://arxiv.org/pdf/1804.05172](http://arxiv.org/pdf/1804.05172)

