---
layout: post
title: "Hierarchical Novelty Detection for Visual Object Recognition"
date: 2018-04-02 20:36:43
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Detection Recognition
author: Kibok Lee, Kimin Lee, Kyle Min, Yuting Zhang, Jinwoo Shin, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved impressive success in large-scale visual object recognition tasks with a predefined set of classes. However, recognizing objects of novel classes unseen during training still remains challenging. The problem of detecting such novel classes has been addressed in the literature, but most prior works have focused on providing simple binary or regressive decisions, e.g., the output would be "known," "novel," or corresponding confidence intervals. In this paper, we study more informative novelty detection schemes based on a hierarchical classification framework. For an object of a novel class, we aim for finding its closest super class in the hierarchical taxonomy of known classes. To this end, we propose two different approaches termed top-down and flatten methods, and their combination as well. The essential ingredients of our methods are confidence-calibrated classifiers, data relabeling, and the leave-one-out strategy for modeling novel classes under the hierarchical taxonomy. Furthermore, our method can generate a hierarchical embedding that leads to improved generalized zero-shot learning performance in combination with other commonly-used semantic embeddings.

##### Abstract (translated by Google)
深度神经网络在具有预定义类别的大规模视觉对象识别任务中取得了令人瞩目的成功。然而，在培训期间识别新类未被看见的对象仍然具有挑战性。在文献中已经讨论了检测这种新类的问题，但是大多数先前的着作集中于提供简单的二元或回归决策，例如输出将是“已知的”，“新颖的”或对应的置信区间。在本文中，我们研究更多的基于分层分类框架的信息新颖性检测方案。对于一个新类的对象，我们的目标是在已知类的分层分类中找到它最接近的超类。为此，我们提出了两种不同的方法，称为自顶向下和扁平化方法，以及它们的组合。我们方法的基本组成部分是置信度校正分类器，数据重新标记以及在分层分类法下对新类进行建模的“一次退出”策略。此外，我们的方法可以生成分层嵌入，结合其他常用的语义嵌入，可以提高广义零点学习性能。

##### URL
[https://arxiv.org/abs/1804.00722](https://arxiv.org/abs/1804.00722)

##### PDF
[https://arxiv.org/pdf/1804.00722](https://arxiv.org/pdf/1804.00722)

