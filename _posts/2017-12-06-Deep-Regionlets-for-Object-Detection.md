---
layout: post
title: "Deep Regionlets for Object Detection"
date: 2017-12-06 21:05:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Hongyu Xu, Xutao Lv, Xiaoyu Wang, Zhou Ren, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
A key challenge in generic object detection is being to handle large variations in object scale, poses, viewpoints, especially part deformations when determining the location for specified object categories. Recent advances in deep neural networks have achieved promising results for object detection by extending the traditional detection methodologies using the convolutional neural network architectures. In this paper, we make an attempt to incorporate another traditional detection schema, Regionlet into an end-to-end trained deep learning framework, and perform ablation studies on its behavior on multiple object detection datasets. More specifically, we propose a "region selection network" and a "gating network". The region selection network serves as a guidance on where to select regions to learn the features from. Additionally, the gating network serves as a local feature selection module to select and transform feature maps to be suitable for detection task. It acts as soft Regionlet selection and pooling. The proposed network is trained end-to-end without additional efforts. Extensive experiments and analysis on the PASCAL VOC dataset and Microsoft COCO dataset show that the proposed framework achieves comparable state-of-the-art results.

##### Abstract (translated by Google)
通用对象检测中的关键挑战是在确定指定对象类别的位置时处理对象比例，姿态，视点，特别是部分变形中的大的变化。深度神经网络的最新进展通过使用卷积神经网络结构扩展了传统的检测方法，在物体检测方面取得了有希望的结果。在本文中，我们试图将另一个传统的检测模式，Regionlet纳入到端到端的训练深度学习框架中，并对其在多个对象检测数据集上的行为进行消融研究。更具体地说，我们提出了“区域选择网络”和“门控网络”。区域选择网络作为从哪里选择区域来学习功能的指导。另外，门控网络作为本地特征选择模块，用于选择和转换特征地图以适合检测任务。它作为软Regionlet选择和池。拟议的网络是经过端对端培训的，没有额外的努力。 PASCAL VOC数据集和Microsoft COCO数据集的大量实验和分析表明，所提出的框架实现了可比较的最先进的结果。

##### URL
[http://arxiv.org/abs/1712.02408](http://arxiv.org/abs/1712.02408)

##### PDF
[http://arxiv.org/pdf/1712.02408](http://arxiv.org/pdf/1712.02408)

