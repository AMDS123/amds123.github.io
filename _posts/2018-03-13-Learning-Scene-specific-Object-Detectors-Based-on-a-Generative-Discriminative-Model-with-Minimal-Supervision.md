---
layout: post
title: "Learning Scene-specific Object Detectors Based on a Generative-Discriminative Model with Minimal Supervision"
date: 2018-03-13 01:58:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Dapeng Luo, Zhipeng Zeng, Nong Sang, Xiang Wu, Longsheng Wei, Quanzheng Mou, Jun Cheng, Chen Luo
mathjax: true
---

* content
{:toc}

##### Abstract
One object class may show large variations due to diverse illuminations, backgrounds and camera viewpoints. Traditional object detection methods often perform worse under unconstrained video environments. To address this problem, many modern approaches model deep hierarchical appearance representations for object detection. Most of these methods require a timeconsuming training process on large manual labelling sample set. In this paper, the proposed framework takes a remarkably different direction to resolve the multi-scene detection problem in a bottom-up fashion. First, a scene-specific objector is obtained from a fully autonomous learning process triggered by marking several bounding boxes around the object in the first video frame via a mouse. Here the human labeled training data or a generic detector are not needed. Second, this learning process is conveniently replicated many times in different surveillance scenes and results in particular detectors under various camera viewpoints. Thus, the proposed framework can be employed in multi-scene object detection applications with minimal supervision. Obviously, the initial scene-specific detector, initialized by several bounding boxes, exhibits poor detection performance and is difficult to improve with traditional online learning algorithm. Consequently, we propose Generative-Discriminative model to partition detection response space and assign each partition an individual descriptor that progressively achieves high classification accuracy. A novel online gradual optimized process is proposed to optimize the Generative-Discriminative model and focus on the hard samples.Experimental results on six video datasets show our approach achieves comparable performance to robust supervised methods, and outperforms the state of the art self-learning methods under varying imaging conditions.

##### Abstract (translated by Google)
由于不同的照明，背景和照相机视点，一个对象类可能会出现较大的变化。传统的物体检测方法在无约束的视频环境下通常表现更差。为了解决这个问题，许多现代的方法为对象检测建立深层次的外观表示模型。大多数这些方法都需要在大型手动标记样本集上进行耗时的训练过程。在本文中，所提出的框架以自下而上的方式解决多场景检测问题的方向非常不同。首先，通过鼠标在第一视频帧中围绕对象标记多个边界框而触发的完全自主学习过程获得场景特定的反对者。这里不需要人工标记的训练数据或通用检测器。其次，这种学习过程在不同的监视场景中被方便地多次复制，并且在各种相机视点下产生特定的探测器。因此，所提出的框架可以在最小监督下用于多场景对象检测应用。显然，初始的特定场景检测器由多个边界框初始化，检测性能较差，传统的在线学习算法难以改进。因此，我们提出了生成 - 区分模型来分割检测响应空间并为每个分区分配一个逐步实现高分类准确性的单独描述符。提出了一种新的在线逐步优化过程来优化生成 - 判别模型，并将重点放在硬样本上。对六个视频数据集的实验结果表明，我们的方法实现了与鲁棒监督方法相当的性能，并且优于现有的自学习方法在不同的成像条件下。

##### URL
[http://arxiv.org/abs/1611.03968](http://arxiv.org/abs/1611.03968)

##### PDF
[http://arxiv.org/pdf/1611.03968](http://arxiv.org/pdf/1611.03968)

