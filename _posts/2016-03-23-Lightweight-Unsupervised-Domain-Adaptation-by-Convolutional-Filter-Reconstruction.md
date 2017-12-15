---
layout: post
title: "Lightweight Unsupervised Domain Adaptation by Convolutional Filter Reconstruction"
date: 2016-03-23 15:28:29
categories: arXiv_CV
tags: arXiv_CV CNN
author: Rahaf Aljundi, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end learning methods have achieved impressive results in many areas of computer vision. At the same time, these methods still suffer from a degradation in performance when testing on new datasets that stem from a different distribution. This is known as the domain shift effect. Recently proposed adaptation methods focus on retraining the network parameters. However, this requires access to all (labeled) source data, a large amount of (unlabeled) target data, and plenty of computational resources. In this work, we propose a lightweight alternative, that allows adapting to the target domain based on a limited number of target samples in a matter of minutes rather than hours, days or even weeks. To this end, we first analyze the output of each convolutional layer from a domain adaptation perspective. Surprisingly, we find that already at the very first layer, domain shift effects pop up. We then propose a new domain adaptation method, where first layer convolutional filters that are badly affected by the domain shift are reconstructed based on less affected ones. This improves the performance of the deep network on various benchmark datasets.

##### Abstract (translated by Google)
端到端的学习方法在许多计算机视觉领域取得了令人瞩目的成果。与此同时，这些方法在对不同分布产生的新数据集进行测试时仍然会受到性能下降的影响。这被称为域转移效应。最近提出的适应方法着重于重新训练网络参数。然而，这需要访问所有（标记的）源数据，大量的（未标记的）目标数据和大量的计算资源。在这项工作中，我们提出了一个轻量级的替代方案，它允许在几分钟而不是几小时，几天甚至几周的基础上，根据有限数量的目标样本来适应目标域。为此，我们首先从领域适应的角度分析每个卷积层的输出。令人惊讶的是，我们发现在第一层已经出现了域名转换效应。然后，我们提出了一个新的领域适应方法，其中第一层卷积滤波器是严重影响的域位移重构的基础上较少受影响的。这提高了各种基准数据集上深度网络的性能。

##### URL
[https://arxiv.org/abs/1603.07234](https://arxiv.org/abs/1603.07234)

##### PDF
[https://arxiv.org/pdf/1603.07234](https://arxiv.org/pdf/1603.07234)

