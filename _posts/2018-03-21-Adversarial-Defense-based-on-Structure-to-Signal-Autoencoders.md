---
layout: post
title: "Adversarial Defense based on Structure-to-Signal Autoencoders"
date: 2018-03-21 16:25:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Relation
author: Joachim Folz, Sebastian Palacio, Joern Hees, Damian Borth, Andreas Dengel
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial attack methods have demonstrated the fragility of deep neural networks. Their imperceptible perturbations are frequently able fool classifiers into potentially dangerous misclassifications. We propose a novel way to interpret adversarial perturbations in terms of the effective input signal that classifiers actually use. Based on this, we apply specially trained autoencoders, referred to as S2SNets, as defense mechanism. They follow a two-stage training scheme: first unsupervised, followed by a fine-tuning of the decoder, using gradients from an existing classifier. S2SNets induce a shift in the distribution of gradients propagated through them, stripping them from class-dependent signal. We analyze their robustness against several white-box and gray-box scenarios on the large ImageNet dataset. Our approach reaches comparable resilience in white-box attack scenarios as other state-of-the-art defenses in gray-box scenarios. We further analyze the relationships of AlexNet, VGG 16, ResNet 50 and Inception v3 in adversarial space, and found that VGG 16 is the easiest to fool, while perturbations from ResNet 50 are the most transferable.

##### Abstract (translated by Google)
敌对攻击方法已经证明了深度神经网络的脆弱性。它们难以察觉的扰动常常使傻瓜分类器变成潜在危险的错误分类。我们提出了一种新颖的方法来解释分类器实际使用的有效输入信号的对抗性干扰。基于此，我们将经过特殊训练的自编码器（称为S2SNets）用作防御机制。他们遵循两阶段训练方案：首先是无监督的，然后是使用现有分类器的梯度对解码器进行微调。 S2SNets引起通过它们传播的梯度分布的变化，从类依赖信号中剥离它们。我们分析它们在大型ImageNet数据集上的几种白盒和灰盒方案的鲁棒性。我们的方法在灰盒方案中与其他最先进的防御方案相比，在白盒攻击方案中具有可比较的恢复能力。我们进一步分析了AlexNet，VGG 16，ResNet 50和Inception v3在敌对空间中的关系，发现VGG 16是最容易被愚弄的，而ResNet 50的扰动是最容易转移的。

##### URL
[http://arxiv.org/abs/1803.07994](http://arxiv.org/abs/1803.07994)

##### PDF
[http://arxiv.org/pdf/1803.07994](http://arxiv.org/pdf/1803.07994)

