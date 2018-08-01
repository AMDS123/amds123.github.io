---
layout: post
title: "Gender Privacy: An Ensemble of Semi Adversarial Networks for Confounding Arbitrary Gender Classifiers"
date: 2018-07-31 17:53:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Face CNN
author: Vahid Mirjalili, Sebastian Raschka, Arun Ross
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research has proposed the use of Semi Adversarial Networks (SAN) for imparting privacy to face images. SANs are convolutional autoencoders that perturb face images such that the perturbed images cannot be reliably used by an attribute classifier (e.g., a gender classifier) but can still be used by a face matcher for matching purposes. However, the generalizability of SANs across multiple arbitrary gender classifiers has not been demonstrated in the literature. In this work, we tackle the generalization issue by designing an ensemble SAN model that generates a diverse set of perturbed outputs for a given input face image. This is accomplished by enforcing diversity among the individual models in the ensemble through the use of different data augmentation techniques. The goal is to ensure that at least one of the perturbed output faces will confound an arbitrary, previously unseen gender classifier. Extensive experiments using different unseen gender classifiers and face matchers are performed to demonstrate the efficacy of the proposed paradigm in imparting gender privacy to face images.

##### Abstract (translated by Google)
最近的研究已经提出使用半对抗网络（SAN）来为面部图像赋予隐私。 SAN是卷积自动编码器，其扰乱面部图像，使得被扰动的图像不能被属性分类器（例如，性别分类器）可靠地使用，但是仍然可以由面部匹配器用于匹配目的。然而，文献中没有证明SAN在多个任意性别分类器中的普遍性。在这项工作中，我们通过设计一个集合SAN模型来解决泛化问题，该模型为给定的输入面部图像生成一组不同的扰动输出。这是通过使用不同的数据增强技术在集合中的各个模型之间实现多样性来实现的。目标是确保至少有一个扰动的输出面将混淆任意的，以前看不见的性别分类器。使用不同的看不见的性别分类器和面部匹配器进行了广泛的实验，以证明所提出的范例在赋予面部图像性别隐私方面的功效。

##### URL
[http://arxiv.org/abs/1807.11936](http://arxiv.org/abs/1807.11936)

##### PDF
[http://arxiv.org/pdf/1807.11936](http://arxiv.org/pdf/1807.11936)

