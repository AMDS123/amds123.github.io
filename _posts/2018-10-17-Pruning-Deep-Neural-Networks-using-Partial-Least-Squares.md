---
layout: post
title: "Pruning Deep Neural Networks using Partial Least Squares"
date: 2018-10-17 15:24:21
categories: arXiv_CV
tags: arXiv_CV CNN
author: Artur Jordao, Fernando Yamada, William Robson Schwartz
mathjax: true
---

* content
{:toc}

##### Abstract
To handle the high computational cost in deep convolutional networks, recent approaches have proposed to find and remove unimportant filters in these networks. Although achieving remarkable results, these approaches demand a high computational cost mostly because the pruning is performed layer-by-layer, which requires many fine-tuning iterations. In this work, we propose a novel approach to efficiently remove filters in deep convolutional neural networks based on Partial Least Squares and Variable Importance in Projection to measure the importance of each filter, removing the unimportant (or least important) ones. We validate the proposed method on ImageNet, Cifar-10 and Food-101 datasets, where it eliminates up to 65% of the filters and reduces 88% of the floating point operations (FLOPs) without penalizing the network accuracy. Additionally, sometimes the method is even able to improve the accuracy compared to the network without pruning. Finally, we show that the proposed method is more efficient and achieves a higher reduction in FLOPs than existing methods. Codes are available at https://github.com/arturjordao/PruningNeuralNetworks

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07610](http://arxiv.org/abs/1810.07610)

##### PDF
[http://arxiv.org/pdf/1810.07610](http://arxiv.org/pdf/1810.07610)

