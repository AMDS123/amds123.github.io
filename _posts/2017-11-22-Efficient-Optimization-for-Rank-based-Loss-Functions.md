---
layout: post
title: "Efficient Optimization for Rank-based Loss Functions"
date: 2017-11-22 11:37:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition Optimization Inference Detection Recognition
author: Pritish Mohapatra, Michal Rolinek, C.V. Jawahar, Vladimir Kolmogorov, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
The accuracy of information retrieval systems is often measured using complex loss functions such as the average precision (AP) or the normalized discounted cumulative gain (NDCG). Given a set of positive (relevant) and negative (non-relevant) samples, the parameters of a retrieval system can be estimated by minimizing these loss functions. However, the non-differentiability and non-decomposability of these loss functions does not allow for simple gradient based optimization algorithms. This issue is generally circumvented by either optimizing a structured hinge-loss upper bound to the loss function or by using asymptotic methods like the direct-loss minimization framework. Yet, the high computational complexity of loss-augmented inference, which is necessary for both the frameworks, prohibits its use in large training data sets. To alleviate this deficiency, we present a novel quicksort flavored algorithm for a large class of non-decomposable loss functions. We provide a complete characterization of the loss functions that are amenable to our algorithm, and show that it includes both AP and NDCG based loss functions. Furthermore, we prove that no comparison based algorithm can improve upon the computational complexity of our approach asymptotically. We demonstrate the effectiveness of our approach in the context of optimizing the structured hinge loss upper bound of AP and NDCG loss for learning models for a variety of vision tasks. Using the CIFAR-10 data set and the PASCAL VOC action recognition and object detection data sets, we show that our approach provides significantly better results than simpler decomposable loss functions, while requiring a comparable training time.

##### Abstract (translated by Google)
信息检索系统的准确性通常使用复杂的损失函数来衡量，如平均精确度（AP）或标准化折扣累积增益（NDCG）。给定一组正面（相关）和负面（不相关）样本，可以通过最小化这些损失函数来估计检索系统的参数。然而，这些损失函数的不可分辨性和不可分解性不允许简单的基于梯度的优化算法。一般通过优化损失函数的结构化铰链损失上限或通过使用像直接损失最小化框架那样的渐近方法来绕过这个问题。然而，这两个框架所必需的损失增强推理的高计算复杂性阻止了其在大型训练数据集中的使用。为了缓解这种不足，我们提出了一种新的快速排序算法，用于一大类不可分解的丢失函数。我们提供了一个完整的损失函数的特征，是适合我们的算法，并表明它包括基于AP和NDCG的损失函数。此外，我们证明没有基于比较的算法可以渐进地改进我们的方法的计算复杂度。我们证明了我们的方法在优化AP和NDCG损失的结构化铰链损失上限的情况下对于各种视觉任务的学习模型的有效性。使用CIFAR-10数据集和PASCAL VOC动作识别和对象检测数据集，我们显示我们的方法比简单的可分解损失函数提供了显着更好的结果，同时需要相当的训练时间。

##### URL
[https://arxiv.org/abs/1604.08269](https://arxiv.org/abs/1604.08269)

##### PDF
[https://arxiv.org/pdf/1604.08269](https://arxiv.org/pdf/1604.08269)

