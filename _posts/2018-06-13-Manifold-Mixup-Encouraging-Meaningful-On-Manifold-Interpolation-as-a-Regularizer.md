---
layout: post
title: "Manifold Mixup: Encouraging Meaningful On-Manifold Interpolation as a Regularizer"
date: 2018-06-13 19:32:59
categories: arXiv_AI
tags: arXiv_AI Adversarial Prediction
author: Vikas Verma, Alex Lamb, Christopher Beckham, Aaron Courville, Ioannis Mitliagkis, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Deep networks often perform well on the data manifold on which they are trained, yet give incorrect (and often very confident) answers when evaluated on points from off of the training distribution. This is exemplified by the adversarial examples phenomenon but can also be seen in terms of model generalization and domain shift. We propose Manifold Mixup which encourages the network to produce more reasonable and less confident predictions at points with combinations of attributes not seen in the training set. This is accomplished by training on convex combinations of the hidden state representations of data samples. Using this method, we demonstrate improved semi-supervised learning, learning with limited labeled data, and robustness to adversarial examples. Manifold Mixup requires no (significant) additional computation. Analytical experiments on both real data and synthetic data directly support our hypothesis for why the Manifold Mixup method improves results.

##### Abstract (translated by Google)
深度网络在他们接受训练的数据流形上经常表现良好，但在从训练分布的点上进行评估时，却给出了不正确（并且往往非常自信）的答案。这可以用对抗例子现象来例证，但也可以从模型泛化和域转移的角度来看。我们提出了Manifold Mixup，它鼓励网络在训练集中没有看到的属性组合点上产生更合理和更不自信的预测。这通过对数据样本的隐藏状态表示的凸组合进行训练来完成。使用这种方法，我们证明了改进的半监督学习，有限的标记数据的学习以及对敌对案例的鲁棒性。歧管混合不需要（显着）额外的计算。实际数据和合成数据的分析实验直接支持我们为什么Manifold Mixup方法改进结果的假设。

##### URL
[https://arxiv.org/abs/1806.05236](https://arxiv.org/abs/1806.05236)

##### PDF
[https://arxiv.org/pdf/1806.05236](https://arxiv.org/pdf/1806.05236)

