---
layout: post
title: "Generative Adversarial Examples"
date: 2018-05-21 05:19:08
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Yang Song, Rui Shu, Nate Kushman, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are typically constructed by perturbing an existing data point, and current defense methods are focused on guarding against this type of attack. In this paper, we propose a new class of adversarial examples that are synthesized entirely from scratch using a conditional generative model. We first train an Auxiliary Classifier Generative Adversarial Network (AC-GAN) to model the class-conditional distribution over inputs. Then, conditioned on a desired class, we search over the AC-GAN latent space to find images that are likely under the generative model and are misclassified by a target classifier. We demonstrate through human evaluation that this new kind of adversarial inputs, which we call Generative Adversarial Examples, are legitimate and belong to the desired class. Our empirical results on the MNIST, SVHN, and CelebA datasets show that generative adversarial examples can easily bypass strong adversarial training and certified defense methods which can foil existing adversarial attacks.

##### Abstract (translated by Google)
敌对的例子通常是通过扰乱现有的数据点来构建的，而当前的防御方法则着重于防范这种类型的攻击。在本文中，我们提出了一类新的对抗性例子，它们完全是从头开始使用条件生成模型进行合成的。我们首先训练一个辅助分类器生成敌对网络（AC-GAN）来对输入的类别条件分布建模。然后，以期望的类别为条件，我们搜索AC-GAN潜在空间以找到可能在生成模型下并被目标分类器错误分类的图像。我们通过人类评估证明，这种新型的敌对投入，我们称之为生成敌对实例，是合法的，属于所需的类别。我们在MNIST，SVHN和CelebA数据集上的实证结果表明，生成对抗的例子可以轻松绕过强大的对抗训练和经过认证的防御方法，这可以打破现有的对抗性攻击。

##### URL
[https://arxiv.org/abs/1805.07894](https://arxiv.org/abs/1805.07894)

##### PDF
[https://arxiv.org/pdf/1805.07894](https://arxiv.org/pdf/1805.07894)

