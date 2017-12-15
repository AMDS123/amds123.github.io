---
layout: post
title: "DisturbLabel: Regularizing CNN on the Loss Layer"
date: 2016-04-30 02:44:48
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Recognition
author: Lingxi Xie, Jingdong Wang, Zhen Wei, Meng Wang, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
During a long period of time we are combating over-fitting in the CNN training process with model regularization, including weight decay, model averaging, data augmentation, etc. In this paper, we present DisturbLabel, an extremely simple algorithm which randomly replaces a part of labels as incorrect values in each iteration. Although it seems weird to intentionally generate incorrect training labels, we show that DisturbLabel prevents the network training from over-fitting by implicitly averaging over exponentially many networks which are trained with different label sets. To the best of our knowledge, DisturbLabel serves as the first work which adds noises on the loss layer. Meanwhile, DisturbLabel cooperates well with Dropout to provide complementary regularization functions. Experiments demonstrate competitive recognition results on several popular image recognition datasets.

##### Abstract (translated by Google)
在很长一段时间内，我们正在打击CNN训练过程中的模型正则化过度拟合，包括权重衰减，模型平均，数据增强等。本文提出了DisturbLabel，这是一种非常简单的算法，可以随机替换部分标签在每次迭代中都是不正确的值。尽管有意识地生成不正确的训练标签似乎很奇怪，但是我们表明，DisturbLabel通过隐式平均指数多的使用不同标签集训练的网络来防止网络训练过度拟合。据我们所知，DisturbLabel是第一个在损耗层上添加噪声的工作。同时，DisturbLabel与Dropout合作，提供互补的正则化功能。实验证明几个流行的图像识别数据集上的竞争性识别结果。

##### URL
[https://arxiv.org/abs/1605.00055](https://arxiv.org/abs/1605.00055)

##### PDF
[https://arxiv.org/pdf/1605.00055](https://arxiv.org/pdf/1605.00055)

