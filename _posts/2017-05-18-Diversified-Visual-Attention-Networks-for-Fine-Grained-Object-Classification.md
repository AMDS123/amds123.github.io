---
layout: post
title: "Diversified Visual Attention Networks for Fine-Grained Object Classification"
date: 2017-05-18 07:36:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention CNN RNN Classification
author: Bo Zhao, Xiao Wu, Jiashi Feng, Qiang Peng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained object classification is a challenging task due to the subtle inter-class difference and large intra-class variation. Recently, visual attention models have been applied to automatically localize the discriminative regions of an image for better capturing critical difference and demonstrated promising performance. However, without consideration of the diversity in attention process, most of existing attention models perform poorly in classifying fine-grained objects. In this paper, we propose a diversified visual attention network (DVAN) to address the problems of fine-grained object classification, which substan- tially relieves the dependency on strongly-supervised information for learning to localize discriminative regions compared with attentionless models. More importantly, DVAN explicitly pursues the diversity of attention and is able to gather discriminative information to the maximal extent. Multiple attention canvases are generated to extract convolutional features for attention. An LSTM recurrent unit is employed to learn the attentiveness and discrimination of attention canvases. The proposed DVAN has the ability to attend the object from coarse to fine granularity, and a dynamic internal representation for classification is built up by incrementally combining the information from different locations and scales of the image. Extensive experiments con- ducted on CUB-2011, Stanford Dogs and Stanford Cars datasets have demonstrated that the proposed diversified visual attention networks achieve competitive performance compared to the state- of-the-art approaches, without using any prior knowledge, user interaction or external resource in training or testing.

##### Abstract (translated by Google)
精细的对象分类是一个具有挑战性的任务，由于微妙的阶级差异和大的课堂内变化。最近，视觉注意模型已经被应用于自动定位图像的区分区域，以更好地捕捉关键差异并展现出有前途的性能。然而，在不考虑注意过程的多样性的情况下，大多数现有的注意模型在对细粒度物体进行分类时表现不佳。在本文中，我们提出了一个多样化的视觉注意网络（DVAN）来解决细粒度的对象分类问题，与无意识模型相比，本质上减轻了依赖于强监督信息的学习来区分局部区域。更重要的是，DVAN明确追求注意力的多样性，并能最大限度地收集歧视信息。生成多个关注画布以提取卷积特征以供注意。利用LSTM复习单元，学习注意力画面的注意力和辨别力。提出的DVAN具有从粗粒到细粒的能力，通过对图像不同位置和尺度的信息进行逐步组合，形成动态的分类内部表示。在CUB-2011上进行了大量的实验，斯坦福大学的狗和斯坦福大学的汽车数据集已经证明，与先进的方法相比，所提出的多样化的视觉关注网络实现了竞争性的表现，而不使用任何现有的知识，用户交互或外部资源在培训或测试。

##### URL
[https://arxiv.org/abs/1606.08572](https://arxiv.org/abs/1606.08572)

##### PDF
[https://arxiv.org/pdf/1606.08572](https://arxiv.org/pdf/1606.08572)

