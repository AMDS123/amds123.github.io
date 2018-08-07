---
layout: post
title: "Structured Adversarial Attack: Towards General Implementation and Better Interpretability"
date: 2018-08-05 18:06:37
categories: arXiv_AI
tags: arXiv_AI Adversarial Sparse
author: Kaidi Xu, Sijia Liu, Pu Zhao, Pin-Yu Chen, Huan Zhang, Deniz Erdogmus, Yanzhi Wang, Xue Lin
mathjax: true
---

* content
{:toc}

##### Abstract
When generating adversarial examples to attack deep neural networks (DNNs), $\ell_p$ norm of the added perturbation is usually used to measure the similarity between original image and adversarial example. However, such adversarial attacks may fail to capture key infomation hidden in the input. This work develops a more general attack model i.e., the structured attack that explores group sparsity in adversarial perturbations by sliding a mask through images aiming for extracting key structures. An ADMM (alternating direction method of multipliers)-based framework is proposed that can split the original problem into a sequence of analytically solvable subproblems and can be generalized to implement other state-of-the-art attacks. Strong group sparsity is achieved in adversarial perturbations even with the same level of distortion in terms of $\ell_p$ norm as the state-of-the-art attacks. Extensive experimental results on MNIST, CIFAR-10 and ImageNet show that our attack could be much stronger (in terms of smaller $\ell_0$ distortion) than the existing ones, and its better interpretability from group sparse structures aids in uncovering the origins of adversarial examples.

##### Abstract (translated by Google)
当生成攻击深度神经网络（DNN）的对抗性示例时，通常使用增加扰动的$ \ ell_p $ norm来测量原始图像和对抗性示例之间的相似性。但是，此类对抗性攻击可能无法捕获隐藏在输入中的关键信息。这项工作开发了一种更通用的攻击模型，即通过在旨在提取关键结构的图像中滑动掩模来探索对抗性扰动中的群体稀疏性的结构化攻击。提出了一种基于ADMM（乘法器的交替方向）的框架，它可以将原始问题分解为一系列可解析的子问题，并且可以推广到实现其他最先进的攻击。在对抗性扰动中实现了强大的群体稀疏性，即使在$ \ ell_p $规范方面具有与最先进的攻击相同的失真水平。关于MNIST，CIFAR-10和ImageNet的大量实验结果表明，我们的攻击可能比现有的攻击强得多（就较小的$ \ ell_0 $失真而言），并且它对群组稀疏结构的更好解释性有助于揭示对抗性的起源。例子。

##### URL
[https://arxiv.org/abs/1808.01664](https://arxiv.org/abs/1808.01664)

##### PDF
[https://arxiv.org/pdf/1808.01664](https://arxiv.org/pdf/1808.01664)

