---
layout: post
title: "DCNNs on a Diet: Sampling Strategies for Reducing the Training Set Size"
date: 2016-06-14 07:38:13
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Maya Kabkab, Azadeh Alavi, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale supervised classification algorithms, especially those based on deep convolutional neural networks (DCNNs), require vast amounts of training data to achieve state-of-the-art performance. Decreasing this data requirement would significantly speed up the training process and possibly improve generalization. Motivated by this objective, we consider the task of adaptively finding concise training subsets which will be iteratively presented to the learner. We use convex optimization methods, based on an objective criterion and feedback from the current performance of the classifier, to efficiently identify informative samples to train on. We propose an algorithm to decompose the optimization problem into smaller per-class problems, which can be solved in parallel. We test our approach on standard classification tasks and demonstrate its effectiveness in decreasing the training set size without compromising performance. We also show that our approach can make the classifier more robust in the presence of label noise and class imbalance.

##### Abstract (translated by Google)
大规模的监督分类算法，特别是基于深度卷积神经网络（DCNNs）的分类算法需要大量的训练数据来实现最新的性能。降低这一数据要求将大大加快培训过程，并可能改进泛化。为了达到这个目标，我们考虑自适应地找到简明的训练子集，这个子集将迭代地呈现给学习者。我们使用凸优化方法，基于客观标准和来自分类器当前性能的反馈，有效地识别信息样本进行训练。我们提出了一种算法来将最优化问题分解成更小的每类问题，并行求解。我们在标准分类任务上测试我们的方法，并证明在减少训练集大小而不影响性能方面的有效性。我们还表明，我们的方法可以使分类器在标签噪声和类别不平衡的情况下更稳健。

##### URL
[https://arxiv.org/abs/1606.04232](https://arxiv.org/abs/1606.04232)

##### PDF
[https://arxiv.org/pdf/1606.04232](https://arxiv.org/pdf/1606.04232)

