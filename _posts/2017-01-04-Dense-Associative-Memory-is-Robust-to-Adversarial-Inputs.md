---
layout: post
title: "Dense Associative Memory is Robust to Adversarial Inputs"
date: 2017-01-04 09:40:09
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Dmitry Krotov, John J Hopfield
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) trained in a supervised way suffer from two known problems. First, the minima of the objective function used in learning correspond to data points (also known as rubbish examples or fooling images) that lack semantic similarity with the training data. Second, a clean input can be changed by a small, and often imperceptible for human vision, perturbation, so that the resulting deformed input is misclassified by the network. These findings emphasize the differences between the ways DNN and humans classify patterns, and raise a question of designing learning algorithms that more accurately mimic human perception compared to the existing methods. Our paper examines these questions within the framework of Dense Associative Memory (DAM) models. These models are defined by the energy function, with higher order (higher than quadratic) interactions between the neurons. We show that in the limit when the power of the interaction vertex in the energy function is sufficiently large, these models have the following three properties. First, the minima of the objective function are free from rubbish images, so that each minimum is a semantically meaningful pattern. Second, artificial patterns poised precisely at the decision boundary look ambiguous to human subjects and share aspects of both classes that are separated by that decision boundary. Third, adversarial images constructed by models with small power of the interaction vertex, which are equivalent to DNN with rectified linear units (ReLU), fail to transfer to and fool the models with higher order interactions. This opens up a possibility to use higher order models for detecting and stopping malicious adversarial attacks. The presented results suggest that DAM with higher order energy functions are closer to human visual perception than DNN with ReLUs.

##### Abstract (translated by Google)
以监督方式训练的深度神经网络（DNN）存在两个已知问题。首先，用于学习的目标函数的最小值对应于与训练数据缺乏语义相似性的数据点（也称为垃圾示例或愚蠢图像）。其次，一个干净的输入可以通过一个小的变化，而且往往不会被人类的视觉，摄动所感知，从而使由此产生的变形输入被网络误分类。这些发现强调了DNN和人类分类方式之间的差异，并提出了与现有方法相比更精确地模拟人类感知的设计学习算法的问题。我们的论文在密集联想记忆（DAM）模型的框架内考察这些问题。这些模型由能量函数定义，具有高阶（高于二次）神经元之间的相互作用。我们证明，当能量函数中交互顶点的能量足够大时，这些模型具有以下三个性质。首先，目标函数的最小值没有垃圾图像，因此每个最小值都是一个语义上有意义的模式。其次，精确地在决策边界上准备的人工模式对于人类主体来说是模棱两可的，并且共享被这个决策边界分开的两个类别的方面。第三，由交互顶点小的权力模型构造的对抗图像，与具有整型线性单位（ReLU）的DNN等价，不能转移到并欺骗具有更高阶交互作用的模型。这就开辟了使用更高阶模型来检测和阻止恶意敌对攻击的可能性。所提出的结果表明，与具有ReLU的DNN相比，具有更高阶能量函数的DAM更接近于人类视觉感知。

##### URL
[https://arxiv.org/abs/1701.00939](https://arxiv.org/abs/1701.00939)

##### PDF
[https://arxiv.org/pdf/1701.00939](https://arxiv.org/pdf/1701.00939)

