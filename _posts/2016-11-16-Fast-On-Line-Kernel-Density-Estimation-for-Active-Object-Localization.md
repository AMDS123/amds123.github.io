---
layout: post
title: "Fast On-Line Kernel Density Estimation for Active Object Localization"
date: 2016-11-16 17:04:35
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Anthony D. Rhodes, Max H. Quinn, Melanie Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
A major goal of computer vision is to enable computers to interpret visual situations---abstract concepts (e.g., "a person walking a dog," "a crowd waiting for a bus," "a picnic") whose image instantiations are linked more by their common spatial and semantic structure than by low-level visual similarity. In this paper, we propose a novel method for prior learning and active object localization for this kind of knowledge-driven search in static images. In our system, prior situation knowledge is captured by a set of flexible, kernel-based density estimations---a situation model---that represent the expected spatial structure of the given situation. These estimations are efficiently updated by information gained as the system searches for relevant objects, allowing the system to use context as it is discovered to narrow the search. More specifically, at any given time in a run on a test image, our system uses image features plus contextual information it has discovered to identify a small subset of training images---an importance cluster---that is deemed most similar to the given test image, given the context. This subset is used to generate an updated situation model in an on-line fashion, using an efficient multipole expansion technique. As a proof of concept, we apply our algorithm to a highly varied and challenging dataset consisting of instances of a "dog-walking" situation. Our results support the hypothesis that dynamically-rendered, context-based probability models can support efficient object localization in visual situations. Moreover, our approach is general enough to be applied to diverse machine learning paradigms requiring interpretable, probabilistic representations generated from partially observed data.

##### Abstract (translated by Google)
计算机视觉的一个主要目标是使计算机能够解释视觉情况 - 抽象的概念（例如，“一个人走路的狗”，“一个等待公共汽车的人群”，“野餐”）的图像实例化更多通过它们共同的空间和语义结构而不是低层次的视觉相似性。在这篇文章中，我们提出了一种新的静态图像知识驱动搜索的先验学习和主动对象定位方法。在我们的系统中，先验知识通过一系列灵活的，基于核的密度估计来捕获 - 一种情境模型---代表给定情境的预期空间结构。这些估计值通过系统搜索相关对象时所获得的信息进行有效更新，从而使系统可以使用发现的上下文缩小搜索范围。更具体地说，在测试图像上运行的任何给定时间，我们的系统使用图像特征加上发现的上下文信息来识别训练图像的小子集---重要性集群---被认为与给出测试图像，给定的上下文。使用高效的多极扩展技术，该子集用于以在线方式生成更新的情况模型。作为一个概念证明，我们将我们的算法应用到由“走狗”情况组成的高度多样化和具有挑战性的数据集中。我们的结果支持动态呈现的基于上下文的概率模型可以在视觉情况下支持高效的对象本地化的假设。此外，我们的方法足够普遍适用于需要部分观察数据产生的可解释的概率表示的各种机器学习范例。

##### URL
[https://arxiv.org/abs/1611.05369](https://arxiv.org/abs/1611.05369)

##### PDF
[https://arxiv.org/pdf/1611.05369](https://arxiv.org/pdf/1611.05369)

