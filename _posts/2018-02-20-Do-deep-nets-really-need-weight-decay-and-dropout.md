---
layout: post
title: "Do deep nets really need weight decay and dropout?"
date: 2018-02-20 10:12:23
categories: arXiv_CV
tags: arXiv_CV Regularization Recognition
author: Alex Hern&#xe1;ndez-Garc&#xed;a, Peter K&#xf6;nig
mathjax: true
---

* content
{:toc}

##### Abstract
The impressive success of modern deep neural networks on computer vision tasks has been achieved through models of very large capacity compared to the number of available training examples. This overparameterization is often said to be controlled with the help of different regularization techniques, mainly weight decay and dropout. However, since these techniques reduce the effective capacity of the model, typically even deeper and wider architectures are required to compensate for the reduced capacity. Therefore, there seems to be a waste of capacity in this practice. In this paper we build upon recent research that suggests that explicit regularization may not be as important as widely believed and carry out an ablation study that concludes that weight decay and dropout may not be necessary for object recognition if enough data augmentation is introduced.

##### Abstract (translated by Google)
现代深度神经网络在计算机视觉任务方面取得的令人印象深刻的成功已经通过与可用训练样例的数量相比超大容量的模型来实现。这种超参数化通常被认为是借助不同的正则化技术来控制的，主要是重量衰减和辍学。但是，由于这些技术会降低模型的有效容量，因此通常需要更深更宽的体系结构来补偿容量降低。因此，这种做法似乎会浪费能力。在本文中，我们基于最近的研究表明，显式正则化可能不如广泛认为的那样重要，并且进行消融研究，得出的结论是，如果引入了足够的数据增量，则物体识别可能不需要重量衰减和辍学。

##### URL
[http://arxiv.org/abs/1802.07042](http://arxiv.org/abs/1802.07042)

##### PDF
[http://arxiv.org/pdf/1802.07042](http://arxiv.org/pdf/1802.07042)

