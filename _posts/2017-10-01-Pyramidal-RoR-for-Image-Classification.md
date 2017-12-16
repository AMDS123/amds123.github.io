---
layout: post
title: "Pyramidal RoR for Image Classification"
date: 2017-10-01 07:34:17
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Prediction
author: Ke Zhang, Liru Guo, Ce Gao, Zhenbing Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
The Residual Networks of Residual Networks (RoR) exhibits excellent performance in the image classification task, but sharply increasing the number of feature map channels makes the characteristic information transmission incoherent, which losses a certain of information related to classification prediction, limiting the classification performance. In this paper, a Pyramidal RoR network model is proposed by analysing the performance characteristics of RoR and combining with the PyramidNet. Firstly, based on RoR, the Pyramidal RoR network model with channels gradually increasing is designed. Secondly, we analysed the effect of different residual block structures on performance, and chosen the residual block structure which best favoured the classification performance. Finally, we add an important principle to further optimize Pyramidal RoR networks, drop-path is used to avoid over-fitting and save training time. In this paper, image classification experiments were performed on CIFAR-10/100 and SVHN datasets, and we achieved the current lowest classification error rates were 2.96%, 16.40% and 1.59%, respectively. Experiments show that the Pyramidal RoR network optimization method can improve the network performance for different data sets and effectively suppress the gradient disappearance problem in DCNN training.

##### Abstract (translated by Google)
剩余网络残差网络（RoR）在图像分类任务中表现出优异的性能，但特征映射通道的数量急剧增加使得特征信息传输不连贯，从而损失了一定的分类预测信息，限制了分类性能。本文通过分析RoR的性能特征，结合PyramidNet，提出了金字塔RoR网络模型。首先，基于RoR，设计了渠道逐渐增多的金字塔式RoR网络模型。其次，分析了不同残差块结构对性能的影响，并选择了最有利于分类性能的残差块结构。最后，为进一步优化金字塔RoR网络增加了一个重要的原则，采用丢弃路径来避免过度拟合，节省训练时间。本文对CIFAR-10/100和SVHN数据集进行了图像分类实验，实现了目前最低的分类错误率分别为2.96％，16.40％和1.59％。实验表明，金字塔RoR网络优化方法可以提高不同数据集的网络性能，有效抑制DCNN训练中的梯度消失问题。

##### URL
[https://arxiv.org/abs/1710.00307](https://arxiv.org/abs/1710.00307)

##### PDF
[https://arxiv.org/pdf/1710.00307](https://arxiv.org/pdf/1710.00307)

