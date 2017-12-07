---
layout: post
title: "Unsupervised learning from video to detect foreground objects in single images"
date: 2017-03-31 14:05:13
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Ioana Croitoru (1), Simion-Vlad Bogolin (1), Marius Leordeanu (1 and 2) ((1) Institute of Mathematics of the Romanian Academy, (2) University "Politehnica" of Bucharest)
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning from visual data is one of the most difficult challenges in computer vision, being a fundamental task for understanding how visual recognition works. From a practical point of view, learning from unsupervised visual input has an immense practical value, as very large quantities of unlabeled videos can be collected at low cost. In this paper, we address the task of unsupervised learning to detect and segment foreground objects in single images. We achieve our goal by training a student pathway, consisting of a deep neural network. It learns to predict from a single input image (a video frame) the output for that particular frame, of a teacher pathway that performs unsupervised object discovery in video. Our approach is different from the published literature that performs unsupervised discovery in videos or in collections of images at test time. We move the unsupervised discovery phase during the training stage, while at test time we apply the standard feed-forward processing along the student pathway. This has a dual benefit: firstly, it allows in principle unlimited possibilities of learning and generalization during training, while remaining very fast at testing. Secondly, the student not only becomes able to detect in single images significantly better than its unsupervised video discovery teacher, but it also achieves state of the art results on two important current benchmarks, YouTube Objects and Object Discovery datasets. Moreover, at test time, our system is at least two orders of magnitude faster than other previous methods.

##### Abstract (translated by Google)
视觉数据的无监督学习是计算机视觉中最困难的挑战之一，是理解视觉识别如何工作的基本任务。从实际的角度来看，从无监督的视觉输入学习具有巨大的实际价值，因为可以以低成本收集非常大量的无标签视频。在本文中，我们解决了无监督学习的任务，以检测和分割单个图像中的前景物体。我们通过训练由深度神经网络组成的学生路径来实现我们的目标。它学习从单一输入图像（视频帧）预测在视频中执行无监督对象发现的教师通路的特定帧的输出。我们的方法不同于在测试时间在视频或图像集合中执行无监督发现的发表文献。在训练阶段，我们移动无监督的发现阶段，而在测试阶段，我们沿着学生路径应用标准的前馈处理。这具有双重好处：首先，原则上允许在训练期间具有无限的学习和概括的可能性，同时保持非常快的测试。其次，学生不仅能够在单个图像中检测出明显优于无监督视频发现的老师，而且还能够在两个重要的当前基准（YouTube对象和对象发现数据集）上实现最先进的效果。而且，在测试时间，我们的系统至少比以前的其他方法快两个数量级。

##### URL
[https://arxiv.org/abs/1703.10901](https://arxiv.org/abs/1703.10901)

##### PDF
[https://arxiv.org/pdf/1703.10901](https://arxiv.org/pdf/1703.10901)

