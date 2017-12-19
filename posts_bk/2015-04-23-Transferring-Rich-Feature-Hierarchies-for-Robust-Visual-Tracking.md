---
layout: post
title: "Transferring Rich Feature Hierarchies for Robust Visual Tracking"
date: 2015-04-23 06:18:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Image_Classification Object_Tracking Classification Detection
author: Naiyan Wang, Siyi Li, Abhinav Gupta, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) models have demonstrated great success in various computer vision tasks including image classification and object detection. However, some equally important tasks such as visual tracking remain relatively unexplored. We believe that a major hurdle that hinders the application of CNN to visual tracking is the lack of properly labeled training data. While existing applications that liberate the power of CNN often need an enormous amount of training data in the order of millions, visual tracking applications typically have only one labeled example in the first frame of each video. We address this research issue here by pre-training a CNN offline and then transferring the rich feature hierarchies learned to online tracking. The CNN is also fine-tuned during online tracking to adapt to the appearance of the tracked target specified in the first video frame. To fit the characteristics of object tracking, we first pre-train the CNN to recognize what is an object, and then propose to generate a probability map instead of producing a simple class label. Using two challenging open benchmarks for performance evaluation, our proposed tracker has demonstrated substantial improvement over other state-of-the-art trackers.

##### Abstract (translated by Google)
卷积神经网络（CNN）模型已经在包括图像分类和对象检测在内的各种计算机视觉任务中展现出巨大的成功。然而，一些同样重要的任务，如视觉跟踪，仍然相对未开发。我们认为阻碍CNN应用于视觉追踪的主要障碍是缺乏适当标记的训练数据。尽管释放CNN能力的现有应用程序经常需要大量的数百万的训练数据，但视频追踪应用程序通常在每个视频的第一帧中只有一个标记示例。我们通过离线预先培训一个CNN来解决这个研究问题，然后把学到的丰富的功能层次转移到在线跟踪上。在线跟踪期间还对CNN进行微调，以适应在第一视频帧中指定的被跟踪目标的外观。为了适应对象跟踪的特点，我们首先对CNN进行预训练，以识别什么是对象，然后提出生成一个概率图，而不是生成一个简单的类标签。使用两个具有挑战性的开放式基准进行性能评估，我们提出的跟踪器已经比其他最先进的跟踪器有了显着的改进。

##### URL
[https://arxiv.org/abs/1501.04587](https://arxiv.org/abs/1501.04587)

##### PDF
[https://arxiv.org/pdf/1501.04587](https://arxiv.org/pdf/1501.04587)

