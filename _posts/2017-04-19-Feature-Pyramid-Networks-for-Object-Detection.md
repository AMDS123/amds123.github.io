---
layout: post
title: "Feature Pyramid Networks for Object Detection"
date: 2017-04-19 22:46:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection Recognition
author: Tsung-Yi Lin, Piotr Dollár, Ross Girshick, Kaiming He, Bharath Hariharan, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Feature pyramids are a basic component in recognition systems for detecting objects at different scales. But recent deep learning object detectors have avoided pyramid representations, in part because they are compute and memory intensive. In this paper, we exploit the inherent multi-scale, pyramidal hierarchy of deep convolutional networks to construct feature pyramids with marginal extra cost. A top-down architecture with lateral connections is developed for building high-level semantic feature maps at all scales. This architecture, called a Feature Pyramid Network (FPN), shows significant improvement as a generic feature extractor in several applications. Using FPN in a basic Faster R-CNN system, our method achieves state-of-the-art single-model results on the COCO detection benchmark without bells and whistles, surpassing all existing single-model entries including those from the COCO 2016 challenge winners. In addition, our method can run at 5 FPS on a GPU and thus is a practical and accurate solution to multi-scale object detection. Code will be made publicly available.

##### Abstract (translated by Google)
特征金字塔是识别系统中用于检测不同尺度物体的基本组件。但是最近的深度学习对象检测器避免了金字塔表示，部分原因是由于它们是计算和内存密集型的。在本文中，我们利用深度卷积网络固有的多尺度，金字塔结构来构造具有边际额外成本的特征金字塔。为了在所有尺度上构建高级语义特征地图，开发了具有横向连接的自顶向下架构。这种称为特征金字塔网络（FPN）的体系结构在几个应用程序中作为通用特征提取器显示出显着的改进。我们的方法在一个基本的更快的R-CNN系统中使用FPN，在COCO检测基准测试中获得了最先进的单模式结果，无需花费大量的时间，超过了所有现有的单模型参赛者，包括来自COCO 2016挑战获胜者。另外，我们的方法可以在GPU上以5 FPS运行，因此是多尺度对象检测的实用和准确的解决方案。代码将被公开。

##### URL
[https://arxiv.org/abs/1612.03144](https://arxiv.org/abs/1612.03144)

##### PDF
[https://arxiv.org/pdf/1612.03144](https://arxiv.org/pdf/1612.03144)

