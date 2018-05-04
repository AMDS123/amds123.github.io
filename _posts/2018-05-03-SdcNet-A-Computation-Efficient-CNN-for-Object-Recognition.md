---
layout: post
title: "SdcNet: A Computation-Efficient CNN for Object Recognition"
date: 2018-05-03 14:16:25
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Yunlong Ma, Chunyan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting features from a huge amount of data for object recognition is a challenging task. Convolution neural network can be used to meet the challenge, but it often requires a large number of computation resources. In this paper, a computation-efficient convolutional module, named SdcBlock, is proposed and based on it, the convolution network SdcNet is introduced for object recognition tasks. In the proposed module, optimized successive depthwise convolutions supported by appropriate data management is applied in order to generate vectors containing high density and more varieties of feature information. The hyperparameters can be easily adjusted to suit varieties of tasks under different computation restrictions without significantly jeopardizing the performance. The experiments have shown that SdcNet achieved an error rate of 5.60\% in CIFAR-10 with only 55M Flops and also reduced further the error rate to 5.24\% using a moderate volume of 103M Flops. The expected computation efficiency of the SdcNet has been confirmed.

##### Abstract (translated by Google)
从大量数据中提取特征用于对象识别是一项具有挑战性的任务。卷积神经网络可以用来迎接挑战，但它往往需要大量的计算资源。本文提出了一种计算效率高的卷积模块SdcBlock，并在此基础上引入卷积网络SdcNet进行物体识别任务。在所提出的模块中，通过适当的数据管理支持的优化的连续深度卷积被应用以生成包含高密度和更多种特征信息的向量。超参数可以很容易地进行调整，以适应不同计算限制下的各种任务，而不会显着影响性能。实验表明，SdcNet在仅有55M触发器的情况下在CIFAR-10中实现了5.60％的错误率，并且还使用中等量的103M触发器将错误率进一步降低至5.24％。 SdcNet的预期计算效率已得到确认。

##### URL
[http://arxiv.org/abs/1805.01317](http://arxiv.org/abs/1805.01317)

##### PDF
[http://arxiv.org/pdf/1805.01317](http://arxiv.org/pdf/1805.01317)

