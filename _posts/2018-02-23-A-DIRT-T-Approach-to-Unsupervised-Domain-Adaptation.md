---
layout: post
title: "A DIRT-T Approach to Unsupervised Domain Adaptation"
date: 2018-02-23 20:57:28
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Recognition
author: Rui Shu, Hung H. Bui, Hirokazu Narui, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation refers to the problem of leveraging labeled data in a source domain to learn an accurate model in a target domain where labels are scarce or unavailable. A recent approach for finding a common representation of the two domains is via domain adversarial training (Ganin &amp; Lempitsky, 2015), which attempts to induce a feature extractor that matches the source and target feature distributions in some feature space. However, domain adversarial training faces two critical limitations: 1) if the feature extraction function has high-capacity, then feature distribution matching is a weak constraint, 2) in non-conservative domain adaptation (where no single classifier can perform well in both the source and target domains), training the model to do well on the source domain hurts performance on the target domain. In this paper, we address these issues through the lens of the cluster assumption, i.e., decision boundaries should not cross high-density data regions. We propose two novel and related models: 1) the Virtual Adversarial Domain Adaptation (VADA) model, which combines domain adversarial training with a penalty term that punishes the violation the cluster assumption; 2) the Decision-boundary Iterative Refinement Training with a Teacher (DIRT-T) model, which takes the VADA model as initialization and employs natural gradient steps to further minimize the cluster assumption violation. Extensive empirical results demonstrate that the combination of these two models significantly improve the state-of-the-art performance on the digit, traffic sign, and Wi-Fi recognition domain adaptation benchmarks.

##### Abstract (translated by Google)
域适应是指利用源域中的标记数据在标签稀缺或不可用的目标域中学习准确模型的问题。最近找到两个域的共同表示的方法是通过域对抗训练（Ganin＆amp; Lempitsky，2015），其试图诱导特征提取器匹配某些特征空间中的源和目标特征分布。然而，领域对抗训练面临两个关键限制：1）如果特征提取函数具有高容量，则特征分布匹配是弱约束，2）在非保守领域适应中（其中单个分类器无法在源域和目标域），在源域上训练模型以取得良好效果会损害目标域的性能。在本文中，我们通过聚类假设的透镜来解决这些问题，即决策边界不应该跨越高密度数据区域。我们提出了两种新颖的和相关的模型：1）虚拟对抗域适应（VADA）模型，它将域对抗训练与惩罚违反聚类假设的惩罚项相结合; 2）用教师决策边界迭代细化训练（DIRT-T）模型，该模型将VADA模型作为初始化并采用自然梯度步骤进一步最小化群集假设违反。广泛的实证结果表明，这两种模式的结合显着改善了数字，交通标志和Wi-Fi识别领域适应基准的最新性能。

##### URL
[http://arxiv.org/abs/1802.08735](http://arxiv.org/abs/1802.08735)

##### PDF
[http://arxiv.org/pdf/1802.08735](http://arxiv.org/pdf/1802.08735)

