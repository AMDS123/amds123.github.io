---
layout: post
title: "Query-Efficient Black-box Adversarial Examples"
date: 2017-12-19 18:58:10
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Andrew Ilyas, Logan Engstrom, Anish Athalye, Jessy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Current neural network-based image classifiers are susceptible to adversarial examples, even in the black-box setting, where the attacker is limited to query access without access to gradients. Previous methods --- substitute networks and coordinate-based finite-difference methods --- are either unreliable or query-inefficient, making these methods impractical for certain problems. 
 We introduce a new method for reliably generating adversarial examples under more restricted, practical black-box threat models. First, we apply natural evolution strategies to perform black-box attacks using two to three orders of magnitude fewer queries than previous methods. Second, we introduce a new algorithm to perform targeted adversarial attacks in the partial-information setting, where the attacker only has access to a limited number of target classes. Using these techniques, we successfully perform the first targeted adversarial attack against a commercially deployed machine learning system, the Google Cloud Vision API, in the partial information setting.

##### Abstract (translated by Google)
当前的基于神经网络的图像分类器容易受到敌对的例子，即使在黑盒子设置中，攻击者被限制为查询访问而不能访问梯度。以前的方法---替代网络和基于坐标的有限差分方法---要么是不可靠的，要么是查询效率低的，使得这些方法对于某些问题是不切实际的。
 我们引入了一种新的方法，在更加严格的实际黑盒威胁模型下可靠地生成敌对的例子。首先，我们使用自然进化策略执行黑盒攻击，比以前的方法少二到三个数量级的查询。其次，我们引入一种新的算法来在部分信息设置中执行有针对性的对抗攻击，攻击者只能访问有限数量的目标类。利用这些技术，我们成功地针对商业部署的机器学习系统（Google Cloud Vision API）在部分信息设置中执行了第一次针对性的对抗攻击。

##### URL
[http://arxiv.org/abs/1712.07113](http://arxiv.org/abs/1712.07113)

##### PDF
[http://arxiv.org/pdf/1712.07113](http://arxiv.org/pdf/1712.07113)

