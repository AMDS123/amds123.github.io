---
layout: post
title: "Synthesizing Training Data for Object Detection in Indoor Scenes"
date: 2017-09-08 00:29:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Georgios Georgakis, Arsalan Mousavian, Alexander C. Berg, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of objects in cluttered indoor environments is one of the key enabling functionalities for service robots. The best performing object detection approaches in computer vision exploit deep Convolutional Neural Networks (CNN) to simultaneously detect and categorize the objects of interest in cluttered scenes. Training of such models typically requires large amounts of annotated training data which is time consuming and costly to obtain. In this work we explore the ability of using synthetically generated composite images for training state-of-the-art object detectors, especially for object instance detection. We superimpose 2D images of textured object models into images of real environments at variety of locations and scales. Our experiments evaluate different superimposition strategies ranging from purely image-based blending all the way to depth and semantics informed positioning of the object models into real scenes. We demonstrate the effectiveness of these object detector training strategies on two publicly available datasets, the GMU-Kitchens and the Washington RGB-D Scenes v2. As one observation, augmenting some hand-labeled training data with synthetic examples carefully composed onto scenes yields object detectors with comparable performance to using much more hand-labeled data. Broadly, this work charts new opportunities for training detectors for new objects by exploiting existing object model repositories in either a purely automatic fashion or with only a very small number of human-annotated examples.

##### Abstract (translated by Google)
在混乱的室内环境中检测物体是服务机器人的关键功能之一。计算机视觉中性能最好的对象检测方法利用深度卷积神经网络（CNN）来同时检测和分类在杂乱场景中感兴趣的对象。对这种模型的培训通常需要大量注释的训练数据，这是耗时且昂贵的。在这项工作中，我们探索使用合成生成的合成图像训练最先进的物体探测器，特别是对象实例探测的能力。我们将纹理对象模型的二维图像叠加到各种位置和尺度的真实环境图像中。我们的实验评估了不同的叠加策略，从纯粹基于图像的混合到对象模型的深度和语义通知定位到真实场景。我们在两个公开可用的数据集，GMU-Kitchens和华盛顿RGB-D场景v2中展示这些对象检测器培训策略的有效性。作为一个观察，通过在场景中精心编写的合成示例来增加一些手标记的训练数据，可以得到具有与使用更多手写标记的数据相当的性能的对象检测器。概括地说，这项工作通过利用现有的对象模型库以纯自动的方式或者仅用非常少量的人工注释的例子来为新对象训练检测器绘制新的机会。

##### URL
[https://arxiv.org/abs/1702.07836](https://arxiv.org/abs/1702.07836)

##### PDF
[https://arxiv.org/pdf/1702.07836](https://arxiv.org/pdf/1702.07836)

