---
layout: post
title: "Deep Perm-Set Net: Learn to Predict Sets with Unknown Permutation and Cardinality Using Deep Neural Networks"
date: 2018-05-02 03:49:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization RNN Deep_Learning Prediction Detection
author: S. Hamid Rezatofighi, Roman Kaskman, Farbod T. Motlagh, Qinfeng Shi, Daniel Cremers, Laura Leal-Taixé, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel approach for learning to predict sets with unknown permutation and cardinality using deep neural networks. Even though the output of many real-world problems, e.g. object detection, are naturally expressed as sets of entities, existing deep learning architectures hinder a trivial extension to deal with this unstructured output. Even deep architectures that handle sequential data, such as recurrent neural networks, can only output an ordered set and may not guarantee a valid solution, i.e. a set with unique elements. In this paper, we derive a mathematical formulation for set prediction using feed-forward neural networks, where the output has unknown and unfixed cardinality and permutation. Specifically, in our formulation we incorporate the permutation as unobservable variable and estimate its distribution during the learning process using alternating optimization. We demonstrate the validity of this formulation on two relevant problems including object detection and a complex CAPTCHA test.

##### Abstract (translated by Google)
我们提出了一种新的方法来学习使用深度神经网络来预测具有未知排列和基数的集合。即使许多现实世界问题的输出，例如对象检测自然地表示为实体集合，现有的深度学习体系结构阻碍了处理这种非结构化输出的微小扩展。即使是处理顺序数据的深层体系结构，如递归神经网络，也只能输出一个有序集合，并且不能保证有效的解决方案，即具有独特元素的集合。在本文中，我们推导了一个使用前馈神经网络进行集合预测的数学公式，其中输出具有未知且未固定的基数和排列。具体而言，在我们的公式中，我们将排列组合为不可观测变量，并使用交替优化来估计其在学习过程中的分布。我们证明了这个公式在两个相关问题上的有效性，包括对象检测和复杂的CAPTCHA测试。

##### URL
[https://arxiv.org/abs/1805.00613](https://arxiv.org/abs/1805.00613)

##### PDF
[https://arxiv.org/pdf/1805.00613](https://arxiv.org/pdf/1805.00613)

