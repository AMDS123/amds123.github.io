---
layout: post
title: "Multi-Modal Geometric Learning for Grasping and Manipulation"
date: 2018-03-20 21:54:37
categories: arXiv_RO
tags: arXiv_RO CNN Prediction
author: Jacob Varley, David Watkins-Valls, Peter Allen
mathjax: true
---

* content
{:toc}

##### Abstract
This work provides an architecture that incorporates depth and tactile information to create rich and accurate 3D models useful for robotic manipulation tasks. This is accomplished through the use of a 3D convolutional neural network (CNN). Offline, the network is provided with both depth and tactile information and trained to predict the object's geometry, thus filling in regions of occlusion. At runtime, the network is provided a partial view of an object and tactile information is acquired to augment the captured depth information. The network can then reason about the object's geometry by utilizing both the collected tactile and depth information. We demonstrate that even small amounts of additional tactile information can be incredibly helpful in reasoning about object geometry. This is particularly true when information from depth alone fails to produce an accurate geometric prediction. Our method is benchmarked against and outperforms other visual-tactile approaches to general geometric reasoning. We also provide experimental results comparing grasping success with our method.

##### Abstract (translated by Google)
这项工作提供了一种结合深度和触觉信息的体系结构，以创建用于机器人操作任务的丰富且准确的3D模型。这是通过使用三维卷积神经网络（CNN）完成的。离线时，网络提供深度和触觉信息，并训练预测对象的几何形状，从而填充遮挡区域。在运行时，为网络提供对象的局部视图，并且获取触觉信息以增加捕获的深度信息。网络可以通过利用收集的触觉和深度信息来推断物体的几何形状。我们证明即使少量额外的触觉信息在对物体几何的推理中可以是非常有用的。仅当来自深度的信息不能产生精确的几何预测时，情况尤其如此。我们的方法基于其他基于几何推理的视觉触觉方法，并且优于其他视觉触觉方法。我们还提供了比较抓取成功与我们的方法的实验结果。

##### URL
[http://arxiv.org/abs/1803.07671](http://arxiv.org/abs/1803.07671)

##### PDF
[http://arxiv.org/pdf/1803.07671](http://arxiv.org/pdf/1803.07671)

