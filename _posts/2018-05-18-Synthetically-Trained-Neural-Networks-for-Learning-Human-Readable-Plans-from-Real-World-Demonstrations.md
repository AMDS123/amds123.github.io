---
layout: post
title: "Synthetically Trained Neural Networks for Learning Human-Readable Plans from Real-World Demonstrations"
date: 2018-05-18 05:30:29
categories: arXiv_RO
tags: arXiv_RO CNN Relation
author: Jonathan Tremblay, Thang To, Artem Molchanov, Stephen Tyree, Jan Kautz, Stan Birchfield
mathjax: true
---

* content
{:toc}

##### Abstract
We present a system to infer and execute a human-readable program from a real-world demonstration. The system consists of a series of neural networks to perform perception, program generation, and program execution. Leveraging convolutional pose machines, the perception network reliably detects the bounding cuboids of objects in real images even when severely occluded, after training only on synthetic images using domain randomization. To increase the applicability of the perception network to new scenarios, the network is formulated to predict in image space rather than in world space. Additional networks detect relationships between objects, generate plans, and determine actions to reproduce a real-world demonstration. The networks are trained entirely in simulation, and the system is tested in the real world on the pick-and-place problem of stacking colored cubes using a Baxter robot.

##### Abstract (translated by Google)
我们提供了一个系统来推断和执行一个真实世界演示的人类可读程序。该系统由一系列神经网络组成，以执行感知，程序生成和程序执行。利用卷积式姿态机，即使在严重遮挡的情况下，感知网络也可以在仅使用域随机化对合成图像进行训练之后可靠地检测实际图像中物体的边界长方体。为了增加感知网络对新情景的适用性，网络被制定为在图像空间而不是在世界空间中进行预测。其他网络检测对象之间的关系，生成计划并确定重现真实世界演示的操作。网络完全是在仿真模式下训练的，系统在现实世界中使用Baxter机器人在堆叠彩色立方体的拾放问题上进行了测试。

##### URL
[http://arxiv.org/abs/1805.07054](http://arxiv.org/abs/1805.07054)

##### PDF
[http://arxiv.org/pdf/1805.07054](http://arxiv.org/pdf/1805.07054)

