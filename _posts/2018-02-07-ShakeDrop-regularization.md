---
layout: post
title: "ShakeDrop regularization"
date: 2018-02-07 10:23:54
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Yoshihiro Yamada, Masakazu Iwamura, Koichi Kise
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a powerful regularization method named ShakeDrop regularization. ShakeDrop is inspired by Shake-Shake regularization that decreases error rates by disturbing learning. While Shake-Shake can be applied to only ResNeXt which has multiple branches, ShakeDrop can be applied to not only ResNeXt but also ResNet, Wide ResNet and PyramidNet in a memory efficient way. Important and interesting feature of ShakeDrop is that it strongly disturbs learning by multiplying even a negative factor to the output of a convolutional layer in the forward training pass. The effectiveness of ShakeDrop is confirmed by experiments on CIFAR-10/100 and Tiny ImageNet datasets.

##### Abstract (translated by Google)
本文提出了一个强大的正则化方法ShakeDrop正则化。 ShakeDrop受Shake-Shake正则化的启发，通过干扰学习来降低错误率。虽然Shake-Shake只能应用于具有多个分支的ResNeXt，但ShakeDrop不仅可以应用于ResNeXt，还可以应用于ResNet，Wide ResNet和PyramidNet。 ShakeDrop的一个重要和有趣的特征是，它强大的干扰了学习，即使是在正向训练过程中，卷积层的输出也会产生负面因素。 ShakeDrop的有效性通过在CIFAR-10/100和Tiny ImageNet数据集上的实验得到证实。

##### URL
[https://arxiv.org/abs/1802.02375](https://arxiv.org/abs/1802.02375)

##### PDF
[https://arxiv.org/pdf/1802.02375](https://arxiv.org/pdf/1802.02375)

