---
layout: post
title: "Illuminating Pedestrians via Simultaneous Detection & Segmentation"
date: 2017-06-26 19:05:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Garrick Brazil, Xi Yin, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Pedestrian detection is a critical problem in computer vision with significant impact on safety in urban autonomous driving. In this work, we explore how semantic segmentation can be used to boost pedestrian detection accuracy while having little to no impact on network efficiency. We propose a segmentation infusion network to enable joint supervision on semantic segmentation and pedestrian detection. When placed properly, the additional supervision helps guide features in shared layers to become more sophisticated and helpful for the downstream pedestrian detector. Using this approach, we find weakly annotated boxes to be sufficient for considerable performance gains. We provide an in-depth analysis to demonstrate how shared layers are shaped by the segmentation supervision. In doing so, we show that the resulting feature maps become more semantically meaningful and robust to shape and occlusion. Overall, our simultaneous detection and segmentation framework achieves a considerable gain over the state-of-the-art on the Caltech pedestrian dataset, competitive performance on KITTI, and executes 2x faster than competitive methods.

##### Abstract (translated by Google)
行人检测是计算机视觉中的一个关键问题，对城市自主驾驶的安全性具有重大影响。在这项工作中，我们探讨了如何使用语义分割来提高行人检测精度，同时对网络效率几乎没有影响。我们提出了一个分割输注网络，以实现对语义分割和行人检测的联合监督。当正确放置时，额外的监督有助于引导共享层中的特征变得更加复杂，并有助于下游行人探测器。使用这种方法，我们发现有弱注释的框就足以获得相当的性能收益。我们提供了一个深入的分析，演示如何通过细分监管来形成共享层。在这样做的过程中，我们展示了由此产生的特征映射变得语义上更有意义，并且对形状和遮挡具有鲁棒性。总体而言，我们的同步检测和分割框架在加州理工学院的行人数据集上取得了巨大的进步，在KITTI上的竞争表现也比竞争对手快2倍。

##### URL
[https://arxiv.org/abs/1706.08564](https://arxiv.org/abs/1706.08564)

##### PDF
[https://arxiv.org/pdf/1706.08564](https://arxiv.org/pdf/1706.08564)

