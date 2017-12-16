---
layout: post
title: "First-spike based visual categorization using reward-modulated STDP"
date: 2017-05-25 11:38:16
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Classification Recognition
author: Milad Mozafari, Saeed Reza Kheradpisheh, Timothée Masquelier, Abbas Nowzari-Dalini, Mohammad Ganjtabesh
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) has recently regained popularity, with major achievements such as beating the European game of Go champion. Here, for the first time, we show that RL can be used efficiently to train a spiking neural network (SNN) to perform object recognition in natural images without using an external classifier. We used a feedforward convolutional SNN and a temporal coding scheme where the most strongly activated neurons fire first, while less activated ones fire later, or not at all. In the highest layers, each neuron was assigned to an object category, and it was assumed that the stimulus category was the category of the first neuron to fire. If this assumption was correct, the neuron was rewarded, i.e. spike-timing-dependent plasticity (STDP) was applied, which reinforced the neuron's selectivity. Otherwise, anti-STDP was applied, which encouraged the neuron to learn something else. As demonstrated on various image datasets (Caltech, ETH-80, and NORB), this reward modulated STDP (R-STDP) approach extracted particularly discriminative visual features, whereas classic unsupervised STDP extracts any feature that consistently repeats. As a result, R-STDP outperformed STDP on these datasets. Furthermore, R-STDP is suitable for online learning, and can adapt to drastic changes such as label permutations. Finally, it is worth mentioning that both feature extraction and classification were done with spikes, using at most one spike per neuron. Thus the network is hardware friendly and energy efficient.

##### Abstract (translated by Google)
强化学习（RL）近来重新流行起来，主要成就是打败了欧洲的Go冠军。在这里，我们第一次展示RL可以被有效地用来训练一个尖峰神经网络（SNN）来执行在自然图像中的对象识别而不使用外部分类器。我们使用前馈卷积SNN和时间编码方案，其中最强烈激活的神经元先激发，而较少激活的神经元后来激发，或根本不激发。在最高层中，每个神经元被分配到一个对象类别，并且假设刺激类别是第一个要触发的神经元的类别。如果这种假设是正确的，则神经元得到奖励，即应用穗定时依赖性可塑性（STDP），这增强了神经元的选择性。否则，应用抗STDP，这促使神经元学习其他东西。如在各种图像数据集（Caltech，ETH-80和NORB）上所证实的，这种奖赏调制STDP（R-STDP）方法提取特别有区别性的视觉特征，而经典无监督STDP提取任何一致重复的特征。因此，R-STDP在这些数据集上的表现优于STDP。而且，R-STDP适合在线学习，可以适应标签排列等剧变。最后，值得一提的是，特征提取和分类都是用尖峰完成的，每个神经元最多使用一个尖峰。因此，该网络是硬件友好和能源效率。

##### URL
[https://arxiv.org/abs/1705.09132](https://arxiv.org/abs/1705.09132)

##### PDF
[https://arxiv.org/pdf/1705.09132](https://arxiv.org/pdf/1705.09132)

