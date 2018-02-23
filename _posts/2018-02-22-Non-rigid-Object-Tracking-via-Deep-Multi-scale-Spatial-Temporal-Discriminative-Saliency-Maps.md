---
layout: post
title: "Non-rigid Object Tracking via Deep Multi-scale Spatial-Temporal Discriminative Saliency Maps"
date: 2018-02-22 09:55:29
categories: arXiv_CV
tags: arXiv_CV Salient Tracking CNN Object_Tracking Classification Detection
author: Pingping Zhang, Dong Wang, Huchuan Lu, Hongyu Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an effective non-rigid object tracking method based on spatial-temporal consistent saliency detection. In contrast to most existing trackers that use a bounding box to specify the tracked target, the proposed method can extract the accurate regions of the target as tracking output, which achieves better description of the non-rigid objects while reduces background pollution to the target model. Furthermore, our model has several unique features. First, a tailored deep fully convolutional neural network (TFCN) is developed to model the local saliency prior for a given image region, which not only provides the pixel-wise outputs but also integrates the semantic information. Second, a multi-scale multi-region mechanism is proposed to generate local region saliency maps that effectively consider visual perceptions with different spatial layouts and scale variations. Subsequently, these saliency maps are fused via a weighted entropy method, resulting in a final discriminative saliency map. Finally, we present a non-rigid object tracking algorithm based on the proposed saliency detection method by utilizing a spatial-temporal consistent saliency map (STCSM) model to conduct target-background classification and using a simple fine-tuning scheme for online updating. Numerous experimental results demonstrate that the proposed algorithm achieves competitive performance in comparison with state-of-the-art methods for both saliency detection and visual tracking, especially outperforming other related trackers on the non-rigid object tracking datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于时空一致显着性检测的有效非刚性目标跟踪方法。与大多数现有的使用边界框来指定被跟踪目标的跟踪器相反，所提出的方法可以提取目标的精确区域作为跟踪输出，从而更好地描述非刚性对象，同时减少目标模型的背景污染。此外，我们的模型有几个独特的功能。首先，定制的深全卷积神经网络（TFCN）被开发用于模拟给定图像区域之前的局部显着性，其不仅提供了像素方式的输出，而且还集成了语义信息。其次，提出了一种多尺度多区域机制来生成局部区域显着图，该图有效地考虑具有不同空间布局和尺度变化的视觉感知。随后，这些显着图通过加权熵方法进行融合，产生最终的区分显着性图。最后，我们提出了一种基于提出的显着性检测方法的非刚性目标跟踪算法，利用时空一致显着图（STCSM）模型进行目标背景分类，并使用简单的微调方案进行在线更新。许多实验结果表明，与显着检测和视觉跟踪的最先进方法相比，所提出的算法实现了竞争性能，尤其是在非刚性对象跟踪数据集上优于其他相关跟踪器。

##### URL
[http://arxiv.org/abs/1802.07957](http://arxiv.org/abs/1802.07957)

##### PDF
[http://arxiv.org/pdf/1802.07957](http://arxiv.org/pdf/1802.07957)

