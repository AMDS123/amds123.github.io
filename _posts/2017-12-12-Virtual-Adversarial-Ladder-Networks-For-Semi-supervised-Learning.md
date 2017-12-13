---
layout: post
title: "Virtual Adversarial Ladder Networks For Semi-supervised Learning"
date: 2017-12-12 11:23:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning
author: Saki Shinoda, Daniel E. Worrall, Gabriel J. Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Semi-supervised learning (SSL) partially circumvents the high cost of labeling data by augmenting a small labeled dataset with a large and relatively cheap unlabeled dataset drawn from the same distribution. This paper offers a novel interpretation of two deep learning-based SSL approaches, ladder networks and virtual adversarial training (VAT), as applying distributional smoothing to their respective latent spaces. We propose a class of models that fuse these approaches. We achieve near-supervised accuracy with high consistency on the MNIST dataset using just 5 labels per class: our best model, ladder with layer-wise virtual adversarial noise (LVAN-LW), achieves 1.42% +/- 0.12 average error rate on the MNIST test set, in comparison with 1.62% +/- 0.65 reported for the ladder network. On adversarial examples generated with L2-normalized fast gradient method, LVAN-LW trained with 5 examples per class achieves average error rate 2.4% +/- 0.3 compared to 68.6% +/- 6.5 for the ladder network and 9.9% +/- 7.5 for VAT.

##### Abstract (translated by Google)
半监督学习（SSL）部分规避了标记数据的昂贵成本，即用相同分布的大型且相对便宜的未标记数据集扩充小标记数据集。本文对两种基于深度学习的SSL方法，阶梯网络和虚拟对抗训练（VAT）作了新的解释，将分布平滑应用到它们各自的潜在空间。我们提出一类融合这些方法的模型。我们使用MNIST数据集上的高一致性实现了接近监督的准确性，每个类只有5个标签：我们最好的模型，阶梯式虚拟对抗噪声（LVAN-LW），平均误差率为1.42％+/- 0.12 MNIST测试集，与梯形网络报告的1.62％+/- 0.65相比较。在用L2归一化快速梯度法生成的对抗性例子中，每类训练5个例子的LVAN-LW的平均误差率为2.4％+/- 0.3，而梯形网络为68.6％+/- 6.5和9.9％+/- 7.5为增值税。

##### URL
[http://arxiv.org/abs/1711.07476](http://arxiv.org/abs/1711.07476)

##### PDF
[http://arxiv.org/pdf/1711.07476](http://arxiv.org/pdf/1711.07476)

