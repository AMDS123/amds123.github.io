---
layout: post
title: "Differentiable Learning-to-Group Channels viaGroupable Convolutional Neural Networks"
date: 2019-08-16 06:50:33
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhaoyang Zhang, Jingyu Li, Wenqi Shao, Zhanglin Peng, Ruimao Zhang, Xiaogang Wang, Ping Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Group convolution, which divides the channels of ConvNets into groups, has achieved impressive improvement over the regular convolution operation. However, existing models, eg. ResNeXt, still suffers from the sub-optimal performance due to manually defining the number of groups as a constant over all of the layers. Toward addressing this issue, we present Groupable ConvNet (GroupNet) built by using a novel dynamic grouping convolution (DGConv) operation, which is able to learn the number of groups in an end-to-end manner. The proposed approach has several appealing benefits. (1) DGConv provides a unified convolution representation and covers many existing convolution operations such as regular dense convolution, group convolution, and depthwise convolution. (2) DGConv is a differentiable and flexible operation which learns to perform various convolutions from training data. (3) GroupNet trained with DGConv learns different number of groups for different convolution layers. Extensive experiments demonstrate that GroupNet outperforms its counterparts such as ResNet and ResNeXt in terms of accuracy and computational complexity. We also present introspection and reproducibility study, for the first time, showing the learning dynamics of training group numbers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05867](https://arxiv.org/abs/1908.05867)

##### PDF
[https://arxiv.org/pdf/1908.05867](https://arxiv.org/pdf/1908.05867)

