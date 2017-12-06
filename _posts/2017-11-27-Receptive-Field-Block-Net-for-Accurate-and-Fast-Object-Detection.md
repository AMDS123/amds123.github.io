---
layout: post
title: "Receptive Field Block Net for Accurate and Fast Object Detection"
date: 2017-11-27 05:37:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Songtao Liu, Di Huang, Yunhong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Current top-performing object detectors depend on deep CNN backbones, such as ResNet-101 and Inception, benefiting from their powerful feature representation but suffering from high computational cost. Conversely, some lightweight model based detectors fulfil real time processing, while their accuracies are often criticized. In this paper, we explore an alternative to build a fast and accurate detector by strengthening lightweight features using a crafting mechanism. Inspired by the structure of Receptive Fields (RFs) in human visual systems, we propose a novel RF Block (RFB) module, which takes the relationship between the size and eccentricity of RFs into account, to enhance the discriminability and robustness of features. We further assemble the RFB module to the top of SSD with a lightweight CNN model, constructing the RFB Net detector. To evaluate its effectiveness, experiments are conducted on two major benchmarks and the results show that RFB Net is able to reach the accuracy of advanced very deep backbone network based detectors while keeping the real-time speed. Code is available at this https URL

##### Abstract (translated by Google)
目前性能最好的物体探测器依赖于深度CNN骨干，如ResNet-101和Inception，受益于其强大的特征表示，但是计算成本高。相反，一些基于轻量级模型的检测器能够实时处理，而他们的精度往往受到批评。在本文中，我们探索了一种通过使用制作机制来加强轻量级特征来构建快速而准确的探测器的替代方案。受人类视觉系统中接收场（RFs）结构的启发，我们提出了一种新颖的RF块（RF Block，RFB）模块，将RFs的尺寸和偏心率之间的关系考虑进去，提高了特征的辨别力和鲁棒性。我们进一步将RFB模块与轻量级CNN模型组装到SSD顶部，构建RFB Net检测器。为了评估其有效性，在两个主要基准上进行了实验，结果表明，RFB Net能够在保持实时速度的同时，达到先进的深度骨干网络检测器的精度。代码在这个https URL上可用

##### URL
[https://arxiv.org/abs/1711.07767](https://arxiv.org/abs/1711.07767)

