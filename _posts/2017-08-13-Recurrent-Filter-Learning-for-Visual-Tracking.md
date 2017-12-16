---
layout: post
title: "Recurrent Filter Learning for Visual Tracking"
date: 2017-08-13 08:18:32
categories: arXiv_CV
tags: arXiv_CV Tracking CNN RNN Gradient_Descent
author: Tianyu Yang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Recently using convolutional neural networks (CNNs) has gained popularity in visual tracking, due to its robust feature representation of images. Recent methods perform online tracking by fine-tuning a pre-trained CNN model to the specific target object using stochastic gradient descent (SGD) back-propagation, which is usually time-consuming. In this paper, we propose a recurrent filter generation methods for visual tracking. We directly feed the target's image patch to a recurrent neural network (RNN) to estimate an object-specific filter for tracking. As the video sequence is a spatiotemporal data, we extend the matrix multiplications of the fully-connected layers of the RNN to a convolution operation on feature maps, which preserves the target's spatial structure and also is memory-efficient. The tracked object in the subsequent frames will be fed into the RNN to adapt the generated filters to appearance variations of the target. Note that once the off-line training process of our network is finished, there is no need to fine-tune the network for specific objects, which makes our approach more efficient than methods that use iterative fine-tuning to online learn the target. Extensive experiments conducted on widely used benchmarks, OTB and VOT, demonstrate encouraging results compared to other recent methods.

##### Abstract (translated by Google)
最近使用卷积神经网络（CNN）由于其强大的图像特征表示而在视觉追踪中获得了普及。最近的方法通过使用随机梯度下降（SGD）反向传播（通常是耗时的）来将预先训练的CNN模型微调到特定目标对象来执行在线跟踪。在本文中，我们提出了一种用于视觉跟踪的递归滤波器生成方法。我们将目标的图像块直接馈送到递归神经网络（RNN）以估计用于跟踪的对象特定的滤波器。由于视频序列是一个时空数据，我们将RNN的全连接层的矩阵乘法扩展到特征映射上的卷积运算，保留了目标的空间结构，并且具有内存效率。后续帧中的跟踪对象将被馈送到RNN中，以使生成的滤波器适应目标的外观变化。请注意，一旦我们网络的离线训练过程完成，就不需要针对特定​​对象微调网络，这使得我们的方法比使用迭代微调在线学习目标的方法更有效率。在广泛使用的基准，OTB和VOT上进行的广泛的实验，与其他最近的方法相比，显示出令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1708.03874](https://arxiv.org/abs/1708.03874)

##### PDF
[https://arxiv.org/pdf/1708.03874](https://arxiv.org/pdf/1708.03874)

