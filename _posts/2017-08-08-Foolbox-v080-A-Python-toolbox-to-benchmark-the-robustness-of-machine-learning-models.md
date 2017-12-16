---
layout: post
title: "Foolbox v0.8.0: A Python toolbox to benchmark the robustness of machine learning models"
date: 2017-08-08 03:22:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Classification Deep_Learning
author: Jonas Rauber, Wieland Brendel, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
Even todays most advanced machine learning models are easily fooled by almost imperceptible perturbations of their inputs. Foolbox is a new Python package to generate such adversarial perturbations and to quantify and compare the robustness of machine learning models. It is build around the idea that the most comparable robustness measure is the minimum perturbation needed to craft an adversarial example. To this end, Foolbox provides reference implementations of most published adversarial attack methods alongside some new ones, all of which perform internal hyperparameter tuning to find the minimum adversarial perturbation. Additionally, Foolbox interfaces with most popular deep learning frameworks such as PyTorch, Keras, TensorFlow, Theano and MXNet, provides a straight forward way to add support for other frameworks and allows different adversarial criteria such as targeted misclassification and top-k misclassification as well as different distance measures. The code is licensed under the MIT license and is openly available at this https URL .

##### Abstract (translated by Google)
即使是今天最先进的机器学习模型也很容易受到其输入几乎不可察觉的扰动的困扰。 Foolbox是一个新的Python软件包，用于产生这种对抗性扰动，量化和比较机器学习模型的稳健性。围绕这个想法构建，最可比较的鲁棒性措施是制作对抗性示例所需的最小扰动。为此，Foolbox提供了大多数已发布的敌对攻击方法的参考实现以及一些新的攻击方法，所有这些方法都执行内部超参数调整以发现最小对抗性扰动。此外，Foolbox与PyTorch，Keras，TensorFlow，Theano和MXNet等深度学习框架的接口提供了一种直接的方式来添加对其他框架的支持，并允许不同的对抗标准，如目标错误分类和top-k错误分类以及不同的距离措施。该代码根据MIT许可证进行许可，并可在此https URL中公开获得。

##### URL
[https://arxiv.org/abs/1707.04131](https://arxiv.org/abs/1707.04131)

##### PDF
[https://arxiv.org/pdf/1707.04131](https://arxiv.org/pdf/1707.04131)

