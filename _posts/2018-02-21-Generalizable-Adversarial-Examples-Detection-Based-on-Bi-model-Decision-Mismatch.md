---
layout: post
title: "Generalizable Adversarial Examples Detection Based on Bi-model Decision Mismatch"
date: 2018-02-21 19:43:08
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Detection
author: Jo&#xe3;o Monteiro, Zahid Akhtar, Tiago H. Falk
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have shown phenomenal success in a wide range of applications. However, recent studies have discovered that they are vulnerable to Adversarial Examples, i.e., original samples with added subtle perturbations. Such perturbations are often too small and imperceptible to humans, yet they can easily fool the neural networks. Few defense techniques against adversarial examples have been proposed, but they require modifying the target model or prior knowledge of adversarial examples generation methods. Likewise, their performance remarkably drops upon encountering adversarial example types not used during the training stage. In this paper, we propose a new framework that can be used to enhance DNNs' robustness by detecting adversarial examples. In particular, we employ the decision layer of independently trained models as features for posterior detection. The proposed framework doesn't require any prior knowledge of adversarial examples generation techniques, and can be directly augmented with unmodified off-the-shelf models. Experiments on the standard MNIST and CIFAR10 datasets show that it generalizes well across not only different adversarial examples generation methods but also various additive perturbations. Specifically, distinct binary classifiers trained on top of our proposed features can achieve a high detection rate (&gt;90%) in a set of white-box attacks and maintain this performance when tested against unseen attacks.

##### Abstract (translated by Google)
深度神经网络（DNN）在广泛的应用中表现出惊人的成功。然而，最近的研究发现，它们容易受到敌对性例子的影响，即原始样本增加了微妙的扰动。这种扰动通常对人类来说太小而不易察觉，但它们很容易欺骗神经网络。已经提出了几种针对对抗性例子的防御技术，但是它们需要修改目标模型或对抗性例子生成方法的先前知识。同样，在遇到训练阶段没有使用的对抗性示例类型时，他们的表现会显着下降。在本文中，我们提出了一个新的框架，可以通过检测敌对的例子来增强DNN的鲁棒性。特别是，我们使用独立训练模型的决策层作为后验检测的特征。所提出的框架不需要对敌对示例生成技术的任何先验知识，并且可以直接用未修改的现成模型进行增补。对标准MNIST和CIFAR10数据集进行的实验表明，它不仅可以在不同的对抗示例生成方法中很好地进行推广，而且还可以对各种加性干扰进行很好的推广。具体而言，在我们提出的特征之上训练的不同二进制分类器可以在一组白盒攻击中实现高检测率（> 90％），并在针对未知攻击进行测试时保持这种性能。

##### URL
[http://arxiv.org/abs/1802.07770](http://arxiv.org/abs/1802.07770)

##### PDF
[http://arxiv.org/pdf/1802.07770](http://arxiv.org/pdf/1802.07770)

