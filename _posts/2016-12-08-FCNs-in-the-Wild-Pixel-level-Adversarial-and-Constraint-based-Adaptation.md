---
layout: post
title: "FCNs in the Wild: Pixel-level Adversarial and Constraint-based Adaptation"
date: 2016-12-08 14:11:10
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Semantic_Segmentation Prediction
author: Judy Hoffman, Dequan Wang, Fisher Yu, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional models for dense prediction have proven successful for a wide range of visual tasks. Such models perform well in a supervised setting, but performance can be surprisingly poor under domain shifts that appear mild to a human observer. For example, training on one city and testing on another in a different geographic region and/or weather condition may result in significantly degraded performance due to pixel-level distribution shift. In this paper, we introduce the first domain adaptive semantic segmentation method, proposing an unsupervised adversarial approach to pixel prediction problems. Our method consists of both global and category specific adaptation techniques. Global domain alignment is performed using a novel semantic segmentation network with fully convolutional domain adversarial learning. This initially adapted space then enables category specific adaptation through a generalization of constrained weak learning, with explicit transfer of the spatial layout from the source to the target domains. Our approach outperforms baselines across different settings on multiple large-scale datasets, including adapting across various real city environments, different synthetic sub-domains, from simulated to real environments, and on a novel large-scale dash-cam dataset.

##### Abstract (translated by Google)
用于密集预测的完全卷积模型已经被证明对于广泛的视觉任务是成功的。这样的模型在监督环境中表现良好，但是在对于观察者来说看起来温和的域转换下，性能可能会令人惊讶地不好。例如，在一个城市进行培训并在不同的地理区域和/或天气条件下对另一个城市进行测试可能导致由于像素级分布移位而导致性能显着降低。本文介绍了第一种领域自适应语义分割方法，提出了一种无监督对抗方法来解决像素预测问题。我们的方法包括全球和类别特定适应技术。全域对齐使用具有完全卷积域对抗学习的新颖语义分割网络来执行。这个初始适应的空间可以通过强制弱学习的推广实现类别特定的适应，并将空间布局从源到目标域的显式转换。我们的方法优于多个大规模数据集的不同设置的基线，包括跨各种真实的城市环境，不同的合成子域，从模拟到真实的环境，以及新型的大型撞击凸轮数据集。

##### URL
[https://arxiv.org/abs/1612.02649](https://arxiv.org/abs/1612.02649)

##### PDF
[https://arxiv.org/pdf/1612.02649](https://arxiv.org/pdf/1612.02649)

