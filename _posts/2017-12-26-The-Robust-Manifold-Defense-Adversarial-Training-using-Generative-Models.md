---
layout: post
title: "The Robust Manifold Defense: Adversarial Training using Generative Models"
date: 2017-12-26 07:28:14
categories: arXiv_CV
tags: arXiv_CV Adversarial Gradient_Descent
author: Andrew Ilyas, Ajil Jalal, Eirini Asteri, Constantinos Daskalakis, Alexandros G. Dimakis
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are demonstrating excellent performance on several classical vision problems. However, these networks are vulnerable to adversarial examples, minutely modified images that induce arbitrary attacker-chosen output from the network. We propose a mechanism to protect against these adversarial inputs based on a generative model of the data. We introduce a pre-processing step that projects on the range of a generative model using gradient descent before feeding an input into a classifier. We show that this step provides the classifier with robustness against first-order, substitute model, and combined adversarial attacks. Using a min-max formulation, we show that there may exist adversarial examples even in the range of the generator, natural-looking images extremely close to the decision boundary for which the classifier has unjustifiedly high confidence. We show that adversarial training on the generative manifold can be used to make a classifier that is robust to these attacks. 
 Finally, we show how our method can be applied even without a pre-trained generative model using a recent method called the deep image prior. We evaluate our method on MNIST, CelebA and Imagenet and show robustness against the current state of the art attacks.

##### Abstract (translated by Google)
深度神经网络在几个经典视觉问题上表现出优异的性能。然而，这些网络很容易受到敌对的例子，精心修改的图像，导致从网络任意攻击者选择的输出。我们提出了一个机制来防止基于数据生成模型的这些对抗性输入。我们介绍一个预处理步骤，在将输入馈送到分类器之前，使用梯度下降投影生成模型的范围。我们证明这一步提供了分类器对一阶，替代模型和组合敌对攻击的鲁棒性。使用min-max公式，我们发现即使在发生器的范围内也可能存在敌对的例子，看起来很自然的图像非常靠近分类器具有不合理的高置信度的判定边界。我们证明生成流形上的敌对训练可以用来制作对这些攻击有效的分类器。
 最后，我们展示了如何使用最近称为深度图像的方法，即使没有预先训练的生成模型，也可以应用我们的方法。我们在MNIST，CelebA和Imagenet上评估我们的方法，并显示针对当前最先进攻击的稳健性。

##### URL
[http://arxiv.org/abs/1712.09196](http://arxiv.org/abs/1712.09196)

##### PDF
[http://arxiv.org/pdf/1712.09196](http://arxiv.org/pdf/1712.09196)

