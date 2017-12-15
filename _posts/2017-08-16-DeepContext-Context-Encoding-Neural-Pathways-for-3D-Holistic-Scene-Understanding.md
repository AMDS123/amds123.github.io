---
layout: post
title: "DeepContext: Context-Encoding Neural Pathways for 3D Holistic Scene Understanding"
date: 2017-08-16 04:12:50
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yinda Zhang, Mingru Bai, Pushmeet Kohli, Shahram Izadi, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
While deep neural networks have led to human-level performance on computer vision tasks, they have yet to demonstrate similar gains for holistic scene understanding. In particular, 3D context has been shown to be an extremely important cue for scene understanding - yet very little research has been done on integrating context information with deep models. This paper presents an approach to embed 3D context into the topology of a neural network trained to perform holistic scene understanding. Given a depth image depicting a 3D scene, our network aligns the observed scene with a predefined 3D scene template, and then reasons about the existence and location of each object within the scene template. In doing so, our model recognizes multiple objects in a single forward pass of a 3D convolutional neural network, capturing both global scene and local object information simultaneously. To create training data for this 3D network, we generate partly hallucinated depth images which are rendered by replacing real objects with a repository of CAD models of the same object category. Extensive experiments demonstrate the effectiveness of our algorithm compared to the state-of-the-arts. Source code and data are available at this http URL

##### Abstract (translated by Google)
虽然深度神经网络已经导致了人类在计算机视觉任务上的表现，但是他们还没有展示类似的整体场景理解的收益。特别是，3D场景已经被证明是场景理解的一个非常重要的线索 - 但是很少有关于将场景信息与深度模型相结合的研究。本文提出了一种将3D上下文嵌入经过训练的神经网络的拓扑结构以执行整体场景理解的方法。给定描绘3D场景的深度图像，我们的网络将观察到的场景与预定义的3D场景模板对齐，然后推断场景模板内每个对象的存在和位置。在这样做的时候，我们的模型可以在3D卷积神经网络的单个正向通道中识别多个对象，同时捕获全局场景和局部对象信息。为了创建这个三维网络的训练数据，我们生成了部分幻觉的深度图像，这些图像通过用相同对象类别的CAD模型库替换真实对象来呈现。大量的实验证明了我们的算法与现有技术相比的有效性。源代码和数据在这个http URL中可用

##### URL
[https://arxiv.org/abs/1603.04922](https://arxiv.org/abs/1603.04922)

##### PDF
[https://arxiv.org/pdf/1603.04922](https://arxiv.org/pdf/1603.04922)

