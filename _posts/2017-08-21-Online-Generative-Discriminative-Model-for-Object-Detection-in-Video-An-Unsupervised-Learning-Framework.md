---
layout: post
title: "Online Generative-Discriminative Model for Object Detection in Video: An Unsupervised Learning Framework"
date: 2017-08-21 06:17:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Dapeng Luo, Zhipeng Zeng, Longsheng Wei, Chen Luo, Jun Chen, Nong Sang
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional single-view object detection methods often perform worse under unconstrained video environments. To address this problem, many modern multi-view detection approaches model complex 3D appearance representations to predict the optimal viewing angle for detection. Most of these approaches require an intensive training process on large database, collected in advance. In this paper, the proposed framework takes a remarkably different direction to resolve multi-view detection problem in a bottom-up fashion. First, a scene-specific objector is obtained from a fully autonomous learning process triggered by marking several bounding boxes around the object in the first video frame via a mouse. Here the human labeled training data or a generic detector are not needed. Second, this learning process is conveniently replicated many times in different surveillance scenes and results in a particular detector under various camera viewpoints. Thus, the proposed framework can be employed in multi-view object detection applications from unsupervised learning process. Obviously, the initial scene-specific detector, initialed by several bounding boxes, exhibits poor detection performance and is difficult to improve with traditional online learning algorithm. Consequently, we propose Generative-Discriminative model to partition detection response space and assign each partition an individual descriptor that progressively achieves high classification accuracy. A novel online gradual learning algorithm is proposed to train the Generative-Discriminative model automatically and focus online learning on the hard samples: the most informative samples lying around the decision boundary. The output is a hybrid classifier based scene-specific detector which achieves decent performance under different viewing angles.

##### Abstract (translated by Google)
传统的单视点对象检测方法在不受约束的视频环境下通常表现较差。为了解决这个问题，许多现代的多视图检测方法模拟复杂的3D外观表示来预测用于检测的最​​佳视角。这些方法中的大多数都需要对大型数据库进行强化培训，并提前收集。在本文中，所提出的框架以自下而上的方式来解决多视图检测问题的方向明显不同。首先，通过鼠标在第一视频帧中围绕对象标记多个边界框，从完全自主的学习过程中获得场景特定的反对者。这里不需要人工标记的训练数据或通用检测器。其次，这种学习过程在不同的监视场景中被多次方便地复制，并在各种摄像机视点下产生特定的探测器。因此，所提出的框架可用于来自无监督学习过程的多视角对象检测应用。显然，初始场景特定检测器由几个边界框签发，检测性能较差，传统在线学习算法难以改进。因此，我们提出了生成 - 区分模型来划分检测响应空间，并为每个分区分配一个逐步实现高分类准确性的描述符。提出了一种新的在线渐进学习算法来自动训练生成判别模型，并将在线学习重点放在硬样本上：位于决策边界周围的信息最丰富的样本。输出是基于混合分类器的场景特定检测器，在不同的视角下可以获得不俗的表现。

##### URL
[https://arxiv.org/abs/1611.03968](https://arxiv.org/abs/1611.03968)

##### PDF
[https://arxiv.org/pdf/1611.03968](https://arxiv.org/pdf/1611.03968)

