---
layout: post
title: "Beyond Trade-off: Accelerate FCN-based Face Detector with Higher Accuracy"
date: 2018-06-02 10:56:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Face CNN Detection Face_Detection
author: Guanglu Song, Yu Liu, Ming Jiang, Yujie Wang, Junjie Yan, Biao Leng
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional neural network (FCN) has been dominating the game of face detection task for a few years with its congenital capability of sliding-window-searching with shared kernels, which boiled down all the redundant calculation, and most recent state-of-the-art methods such as Faster-RCNN, SSD, YOLO and FPN use FCN as their backbone. So here comes one question: Can we find a universal strategy to further accelerate FCN with higher accuracy, so could accelerate all the recent FCN-based methods? To analyze this, we decompose the face searching space into two orthogonal directions, `scale' and `spatial'. Only a few coordinates in the space expanded by the two base vectors indicate foreground. So if FCN could ignore most of the other points, the searching space and false alarm should be significantly boiled down. Based on this philosophy, a novel method named scale estimation and spatial attention proposal ($S^2AP$) is proposed to pay attention to some specific scales and valid locations in the image pyramid. Furthermore, we adopt a masked-convolution operation based on the attention result to accelerate FCN calculation. Experiments show that FCN-based method RPN can be accelerated by about $4\times$ with the help of $S^2AP$ and masked-FCN and at the same time it can also achieve the state-of-the-art on FDDB, AFW and MALF face detection benchmarks as well.

##### Abstract (translated by Google)
完全卷积神经网络（FCN）由于具有共享内核的滑动窗口搜索的先天性能，一直在支配人脸检测任务的游戏几年，所有这些冗余计算都已经完成，最近的状态诸如Faster-RCNN，SSD，YOLO和FPN之类的现有方法使用FCN作为其主干。所以这里有一个问题：我们能否找到一种通用策略来进一步加快FCN的准确性，从而加速所有基于FCN的方法？为了分析这一点，我们将人脸搜索空间分解为两个正交方向，即“尺度”和“空间”。由两个基矢量扩展的空间中只有几个坐标表示前景。所以如果FCN可以忽略其他大部分的话，那么搜索空间和虚警应该大大降低。基于这一思想，提出了一种新的方法 - 尺度估计和空间关注提议（$ S ^ 2AP $）来关注图像金字塔中的一些具体尺度和有效位置。此外，我们采用基于关注结果的掩蔽卷积运算来加速FCN计算。实验表明，基于FCN的方法RPN在$ S ^ 2AP $和屏蔽FCN的帮助下可以加速大约$ 4 / times $，同时它也可以实现FDDB上的最新技术， AFW和MALF人脸检测基准。

##### URL
[http://arxiv.org/abs/1804.05197](http://arxiv.org/abs/1804.05197)

##### PDF
[http://arxiv.org/pdf/1804.05197](http://arxiv.org/pdf/1804.05197)

