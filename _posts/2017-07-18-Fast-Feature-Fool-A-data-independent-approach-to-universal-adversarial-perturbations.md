---
layout: post
title: "Fast Feature Fool: A data independent approach to universal adversarial perturbations"
date: 2017-07-18 11:48:14
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Optimization Recognition
author: Konda Reddy Mopuri, Utsav Garg, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art object recognition Convolutional Neural Networks (CNNs) are shown to be fooled by image agnostic perturbations, called universal adversarial perturbations. It is also observed that these perturbations generalize across multiple networks trained on the same target data. However, these algorithms require training data on which the CNNs were trained and compute adversarial perturbations via complex optimization. The fooling performance of these approaches is directly proportional to the amount of available training data. This makes them unsuitable for practical attacks since its unreasonable for an attacker to have access to the training data. In this paper, for the first time, we propose a novel data independent approach to generate image agnostic perturbations for a range of CNNs trained for object recognition. We further show that these perturbations are transferable across multiple network architectures trained either on same or different data. In the absence of data, our method generates universal adversarial perturbations efficiently via fooling the features learned at multiple layers thereby causing CNNs to misclassify. Experiments demonstrate impressive fooling rates and surprising transferability for the proposed universal perturbations generated without any training data.

##### Abstract (translated by Google)
最先进的目标识别卷积神经网络（CNN）被图像不可知的扰动所愚弄，被称为通用对抗扰动（universal adversarial perturbations）。还可以观察到，这些扰动在相同的目标数据上训练的多个网络中概括。然而，这些算法需要培训CNNs的训练数据，并通过复杂的优化计算对抗性的扰动。这些方法的愚蠢表现与可用的训练数据量成正比。这使得它们不适合实际的攻击，因为攻击者无法访问训练数据。在本文中，我们第一次提出了一种新颖的数据独立方法来生成一系列CNNs的图像不可知的扰动训练目标识别。我们进一步表明，这些扰动可以跨多个网络体系结构在相同或不同的数据上进行训练。在没有数据的情况下，我们的方法通过愚弄在多个层次学习的特征从而导致CNN错误分类而高效地产生普遍的对抗性扰动。实验证明，在没有任何训练数据的情况下，所提出的通用扰动令人印象深刻的愚弄率和惊人的可转移性。

##### URL
[https://arxiv.org/abs/1707.05572](https://arxiv.org/abs/1707.05572)

##### PDF
[https://arxiv.org/pdf/1707.05572](https://arxiv.org/pdf/1707.05572)

