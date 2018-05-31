---
layout: post
title: "Deep Defense: Training DNNs with Improved Adversarial Robustness"
date: 2018-05-30 01:59:20
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Optimization Classification Prediction
author: Ziang Yan, Yiwen Guo, Changshui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the efficacy on a variety of computer vision tasks, deep neural networks (DNNs) are vulnerable to adversarial attacks, limiting their applications in security-critical systems. Recent works have shown the possibility of generating imperceptibly perturbed image inputs (a.k.a., adversarial examples) to fool well-trained DNN classifiers into making arbitrary predictions. To address this problem, we propose a training recipe named "deep defense". Our core idea is to integrate an adversarial perturbation-based regularizer into the classification objective, such that the obtained models learn to resist potential attacks, directly and precisely. The whole optimization problem is solved just like training a recursive network. Experimental results demonstrate that our method outperforms training with adversarial/Parseval regularizations by large margins on various datasets (including MNIST, CIFAR-10 and ImageNet) and different DNN architectures. Code and models for reproducing our results will be made publicly available.

##### Abstract (translated by Google)
尽管对各种计算机视觉任务有效，但深度神经网络（DNN）容易受到对抗性攻击，限制了它们在安全关键系统中的应用。最近的作品已经显示了产生不可感知的扰动的图像输入（又称敌对性示例）的可能性，以便将训练有素的DNN分类器伪装成任意预测。为了解决这个问题，我们提出了一个名为“深度防御”的训练方法。我们的核心思想是将基于对冲扰动的正规化器整合到分类目标中，以使所获得的模型能够直接而准确地抵御潜在的攻击。整个优化问题就像训练递归网络一样解决。实验结果表明，我们的方法在不同的数据集（包括MNIST，CIFAR-10和ImageNet）和不同的DNN体系结构上胜过大规模利用对抗/ Parseval正则化的训练。复制我们结果的代码和模型将公开发布。

##### URL
[http://arxiv.org/abs/1803.00404](http://arxiv.org/abs/1803.00404)

##### PDF
[http://arxiv.org/pdf/1803.00404](http://arxiv.org/pdf/1803.00404)

