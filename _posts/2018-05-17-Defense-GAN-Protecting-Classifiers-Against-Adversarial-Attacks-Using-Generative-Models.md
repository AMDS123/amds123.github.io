---
layout: post
title: "Defense-GAN: Protecting Classifiers Against Adversarial Attacks Using Generative Models"
date: 2018-05-17 05:38:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Inference Classification
author: Pouya Samangouei, Maya Kabkab, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep neural network approaches have been widely adopted for machine learning tasks, including classification. However, they were shown to be vulnerable to adversarial perturbations: carefully crafted small perturbations can cause misclassification of legitimate images. We propose Defense-GAN, a new framework leveraging the expressive capability of generative models to defend deep neural networks against such attacks. Defense-GAN is trained to model the distribution of unperturbed images. At inference time, it finds a close output to a given image which does not contain the adversarial changes. This output is then fed to the classifier. Our proposed method can be used with any classification model and does not modify the classifier structure or training procedure. It can also be used as a defense against any attack as it does not assume knowledge of the process for generating the adversarial examples. We empirically show that Defense-GAN is consistently effective against different attack methods and improves on existing defense strategies. Our code has been made publicly available at https://github.com/kabkabm/defensegan.

##### Abstract (translated by Google)
近年来，深度神经网络方法已被广泛用于机器学习任务，包括分类。但是，它们被证明容易受到对抗性干扰：精心设计的小扰动会导致合法图像的错误分类。我们提出了Defense-GAN，这是一个利用生成模型的表达能力来保护深度神经网络免受此类攻击的新框架。 Defense-GAN的训练是模拟未干扰图像的分布。在推断时，它会找到一个不包含敌对变化的给定图像的接近输出。这个输出然后被馈送到分类器。我们提出的方法可以用于任何分类模型，不会修改分类器结构或训练过程。它也可以用来防御任何攻击，因为它不会假设生成敌对示例的过程的知识。我们凭经验证明，Defense-GAN始终能够有效抵御不同的攻击方法，并改进现有的防御策略。我们的代码已在https://github.com/kabkabm/defensegan公开发布。

##### URL
[http://arxiv.org/abs/1805.06605](http://arxiv.org/abs/1805.06605)

##### PDF
[http://arxiv.org/pdf/1805.06605](http://arxiv.org/pdf/1805.06605)

