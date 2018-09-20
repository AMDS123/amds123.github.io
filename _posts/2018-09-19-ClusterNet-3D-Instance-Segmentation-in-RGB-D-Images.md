---
layout: post
title: "ClusterNet: 3D Instance Segmentation in RGB-D Images"
date: 2018-09-19 05:23:11
categories: arXiv_AI
tags: arXiv_AI Segmentation
author: Lin Shao, Ye Tian, Jeannette Bohg
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for instance-level segmentation that uses RGB-D data as input and provides detailed information about the location, geometry and number of individual objects in the scene. This level of understanding is fundamental for autonomous robots. It enables safe and robust decision-making under the large uncertainty of the real-world. In our model, we propose to use the first and second order moments of the object occupancy function to represent an object instance. We train an hourglass Deep Neural Network (DNN) where each pixel in the output votes for the 3D position of the corresponding object center and for the object's size and pose. The final instance segmentation is achieved through clustering in the space of moments. The object-centric training loss is defined on the output of the clustering. Our method outperforms the state-of-the-art instance segmentation method on our synthesized dataset. We show that our method generalizes well on real-world data achieving visually better segmentation results.

##### Abstract (translated by Google)
我们提出了一种实例级分割方法，该方法使用RGB-D数据作为输入，并提供有关场景中各个对象的位置，几何和数量的详细信息。这种理解水平对自动机器人至关重要。它可以在现实世界的巨大不确定性下实现安全和稳健的决策。在我们的模型中，我们建议使用对象占用函数的一阶和二阶矩来表示对象实例。我们训练沙漏深度神经网络（DNN），其中输出中的每个像素投票选择相应对象中心的3D位置以及对象的大小和姿势。最后的实例分割是通过在瞬间的空间中进行聚类来实现的。以对象为中心的训练损失是在聚类的输出上定义的。我们的方法在我们的合成数据集上优于最先进的实例分割方法。我们表明，我们的方法很好地概括了实际数据，实现了视觉上更好的分割结果。

##### URL
[http://arxiv.org/abs/1807.08894](http://arxiv.org/abs/1807.08894)

##### PDF
[http://arxiv.org/pdf/1807.08894](http://arxiv.org/pdf/1807.08894)

