---
layout: post
title: "Broadcasting Convolutional Network"
date: 2017-12-07 07:21:04
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Simyung Chang, John Yang, Seonguk Park, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
While convolutional neural networks (CNNs) are widely used for handling spatio-temporal scenes, there exist limitations in reasoning relations among spatial features caused by their inherent structures, which have been issued consistently in many studies. In this paper, we propose Broadcasting Convolutional Networks (BCN) that allow global receptive fields to share spatial information. BCNs are simple network modules that collect effective spatial features, embed location informations and broadcast them to the entire feature maps without much additional computational cost. This method gains great improvements in feature localization problems through efficiently extending the receptive fields, and can easily be implemented within any structure of CNNs. We further utilize BCN to propose Multi-Relational Networks (multiRN) that greatly improve existing Relation Networks (RNs). In pixel-based relation reasoning problems, multiRN with BCNs implanted extends the concept of `pairwise relations' from conventional RNs to `multiple relations' by relating each object with multiple objects at once and not in pairs. This yields in O(n) complexity for n number of objects, which is a vast computational gain from RNs that take O(n^2). Through experiments, BCNs are proven for their usability on relation reasoning problems, which is due from their efficient handlings of spatial information.

##### Abstract (translated by Google)
虽然卷积神经网络（CNNs）被广泛用于处理时空场景，但由于其固有结构引起的空间特征之间的推理关系存在限制，这在许多研究中一直发表。在本文中，我们提出了广播卷积网络（BCN），允许全球接受领域共享空间信息。 BCN是简单的网络模块，可以收集有效的空间特征，嵌入位置信息并将其广播到整个特征地图，而无需额外的计算成本。这种方法通过高效地扩展接受领域，在特征定位问题上得到了很大的改进，并且可以很容易地在任何CNN结构中实现。我们进一步利用BCN来提出多关系网络（multiRN），大大改善现有的关系网络（RN）。在基于像素的关系推理问题中，植入了BCN的multiRN通过将每个对象与多个对象同时关联而不是成对地将“从成对关系”的概念从传统的RN扩展到“多关系”。这对于n个对象产生O（n）复杂度，这是从RN获得的大量计算增益，其中O（n ^ 2）。通过实验，证明BCNs在关系推理问题上的可用性，这是由于它们有效处理空间信息。

##### URL
[http://arxiv.org/abs/1712.02517](http://arxiv.org/abs/1712.02517)

##### PDF
[http://arxiv.org/pdf/1712.02517](http://arxiv.org/pdf/1712.02517)

