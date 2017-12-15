---
layout: post
title: "Once for All: a Two-flow Convolutional Neural Network for Visual Tracking"
date: 2016-04-26 03:34:39
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking
author: Kai Chen, Wenbing Tao
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main challenges of visual object tracking comes from the arbitrary appearance of objects. Most existing algorithms try to resolve this problem as an object-specific task, i.e., the model is trained to regenerate or classify a specific object. As a result, the model need to be initialized and retrained for different objects. In this paper, we propose a more generic approach utilizing a novel two-flow convolutional neural network (named YCNN). The YCNN takes two inputs (one is object image patch, the other is search image patch), then outputs a response map which predicts how likely the object appears in a specific location. Unlike those object-specific approach, the YCNN is trained to measure the similarity between two image patches. Thus it will not be confined to any specific object. Furthermore the network can be end-to-end trained to extract both shallow and deep convolutional features which are dedicated for visual tracking. And once properly trained, the YCNN can be applied to track all kinds of objects without further training and updating. Benefiting from the once-for-all model, our algorithm is able to run at a very high speed of 45 frames-per-second. The experiments on 51 sequences also show that our algorithm achieves an outstanding performance.

##### Abstract (translated by Google)
视觉对象追踪的主要挑战之一来自对象的任意外观。大多数现有的算法都试图将这个问题作为一个对象特定的任务来解决，也就是说，该模型被训练来重新生成或分类一个特定的对象。因此，模型需要针对不同的对象进行初始化和再训练。在本文中，我们提出了一个更通用的方法，利用一种新型的双流卷积神经网络（称为YCNN）。 YCNN需要两个输入（一个是对象图像补丁，另一个是搜索图像补丁），然后输出一个响应图，预测对象出现在特定位置的可能性。与那些特定于对象的方法不同，YCNN被训练来测量两个图像块之间的相似性。因此它不会局限于任何特定的对象。此外，网络可以进行端到端的训练，以提取专用于视觉追踪的浅层和深层卷积特征。一旦训练有素，YCNN可以用于追踪各种物体而无需进一步的训练和更新。受益于一劳永逸的模式，我们的算法能够以每秒45帧的速度运行。 51个序列的实验也证明了我们的算法取得了优异的性能。

##### URL
[https://arxiv.org/abs/1604.07507](https://arxiv.org/abs/1604.07507)

##### PDF
[https://arxiv.org/pdf/1604.07507](https://arxiv.org/pdf/1604.07507)

