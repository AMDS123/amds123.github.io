---
layout: post
title: "Customizing an Adversarial Example Generator with Class-Conditional GANs"
date: 2018-06-27 14:24:27
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Prediction
author: Shih-hong Tsai
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are intentionally crafted data with the purpose of deceiving neural networks into misclassification. When we talk about strategies to create such examples, we usually refer to perturbation-based methods that fabricate adversarial examples by applying invisible perturbations onto normal data. The resulting data reserve their visual appearance to human observers, yet can be totally unrecognizable to DNN models, which in turn leads to completely misleading predictions. In this paper, however, we consider crafting adversarial examples from existing data as a limitation to example diversity. We propose a non-perturbation-based framework that generates native adversarial examples from class-conditional generative adversarial networks.As such, the generated data will not resemble any existing data and thus expand example diversity, raising the difficulty in adversarial defense. We then extend this framework to pre-trained conditional GANs, in which we turn an existing generator into an "adversarial-example generator". We conduct experiments on our approach for MNIST and CIFAR10 datasets and have satisfactory results, showing that this approach can be a potential alternative to previous attack strategies.

##### Abstract (translated by Google)
敌对的例子是故意制作的数据，目的是欺骗神经网络进行错误分类。当我们讨论创建这些例子的策略时，我们通常会提到基于扰动的方法，通过在正常数据上应用不可见的扰动来制造敌对的例子。由此产生的数据将其视觉外观保留给人类观察者，但DNN模型完全无法识别，从而导致完全误导性的预测。然而，在本文中，我们考虑将现有数据中的敌对事例作为对示例多样性的限制。我们提出了一个基于非扰动的框架，可以从类条件生成对抗网络生成本机对抗的例子。因此，生成的数据不会与任何现有数据相似，从而扩大了示例多样性，增加了对抗防御的难度。然后，我们将这个框架扩展到预先训练的条件GAN，其中我们将现有的发电机变成一个“敌对的示例发电机”。我们针对MNIST和CIFAR10数据集的方法进行了实验，结果令人满意，表明这种方法可以替代先前的攻击策略。

##### URL
[http://arxiv.org/abs/1806.10496](http://arxiv.org/abs/1806.10496)

##### PDF
[http://arxiv.org/pdf/1806.10496](http://arxiv.org/pdf/1806.10496)

