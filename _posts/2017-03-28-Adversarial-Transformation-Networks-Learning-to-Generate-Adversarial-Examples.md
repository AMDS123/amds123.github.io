---
layout: post
title: "Adversarial Transformation Networks: Learning to Generate Adversarial Examples"
date: 2017-03-28 03:24:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Classification
author: Shumeet Baluja, Ian Fischer
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple different approaches of generating adversarial examples have been proposed to attack deep neural networks. These approaches involve either directly computing gradients with respect to the image pixels, or directly solving an optimization on the image pixels. In this work, we present a fundamentally new method for generating adversarial examples that is fast to execute and provides exceptional diversity of output. We efficiently train feed-forward neural networks in a self-supervised manner to generate adversarial examples against a target network or set of networks. We call such a network an Adversarial Transformation Network (ATN). ATNs are trained to generate adversarial examples that minimally modify the classifier's outputs given the original input, while constraining the new classification to match an adversarial target class. We present methods to train ATNs and analyze their effectiveness targeting a variety of MNIST classifiers as well as the latest state-of-the-art ImageNet classifier Inception ResNet v2.

##### Abstract (translated by Google)
已经提出了多种不同的生成对抗性例子的方法来攻击深度神经网络。这些方法涉及直接计算相对于图像像素的梯度，或者直接求解图像像素的优化。在这项工作中，我们提出了一个全新的方法来产生敌对的例子，这个例子很快执行，并提供了出色的多样性。我们有效地训练前馈神经网络在一个自我监督的方式来产生针对目标网络或网络组的敌对的例子。我们称这种网络为敌对转换网络（ATN）。 ATNs被训练产生敌对的例子，在给定原始输入的情况下最小地修改分类器的输出，同时约束新的分类以匹配敌对的目标类别。我们提出了训练ATN的方法，并分析了它们针对各种MNIST分类器以及最新的最先进的ImageNet分类器Inception ResNet v2的有效性。

##### URL
[https://arxiv.org/abs/1703.09387](https://arxiv.org/abs/1703.09387)

##### PDF
[https://arxiv.org/pdf/1703.09387](https://arxiv.org/pdf/1703.09387)

