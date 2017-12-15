---
layout: post
title: "Adversarial examples in the physical world"
date: 2017-02-11 00:39:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Alexey Kurakin, Ian Goodfellow, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing machine learning classifiers are highly vulnerable to adversarial examples. An adversarial example is a sample of input data which has been modified very slightly in a way that is intended to cause a machine learning classifier to misclassify it. In many cases, these modifications can be so subtle that a human observer does not even notice the modification at all, yet the classifier still makes a mistake. Adversarial examples pose security concerns because they could be used to perform an attack on machine learning systems, even if the adversary has no access to the underlying model. Up to now, all previous work have assumed a threat model in which the adversary can feed data directly into the machine learning classifier. This is not always the case for systems operating in the physical world, for example those which are using signals from cameras and other sensors as an input. This paper shows that even in such physical world scenarios, machine learning systems are vulnerable to adversarial examples. We demonstrate this by feeding adversarial images obtained from cell-phone camera to an ImageNet Inception classifier and measuring the classification accuracy of the system. We find that a large fraction of adversarial examples are classified incorrectly even when perceived through the camera.

##### Abstract (translated by Google)
大多数现有的机器学习分类器非常容易受到敌对的例子。一个对抗性的例子是一个输入数据的样本，这个数据被修改得非常少，以致机器学习分类器将其误分类。在很多情况下，这些修改可能非常微妙，以至于人类观察者甚至根本不会注意到修改，但分类器仍然是错误的。敌对的例子带来了安全问题，因为即使对手无法访问底层模型，它们也可能被用来对机器学习系统进行攻击。到目前为止，所有以前的工作都假设了一个威胁模型，在这个模型中，攻击者可以直接向机器学习分类器提供数据。在物理世界中运行的系统并不总是这种情况，例如那些使用来自相机和其他传感器的信号作为输入的情况。本文表明，即使在这样的物理世界情景下，机器学习系统也容易受到敌对的例子。我们通过将从手机相机获得的敌对图像提供给ImageNet Inception分类器并测量系统的分类准确度来证明这一点。我们发现，即使通过相机感知，很大一部分敌对的例子也被错误地分类。

##### URL
[https://arxiv.org/abs/1607.02533](https://arxiv.org/abs/1607.02533)

##### PDF
[https://arxiv.org/pdf/1607.02533](https://arxiv.org/pdf/1607.02533)

