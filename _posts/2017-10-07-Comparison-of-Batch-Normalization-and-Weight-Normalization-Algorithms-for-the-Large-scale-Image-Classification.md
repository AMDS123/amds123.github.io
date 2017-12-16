---
layout: post
title: "Comparison of Batch Normalization and Weight Normalization Algorithms for the Large-scale Image Classification"
date: 2017-10-07 23:28:57
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Image_Classification Classification
author: Igor Gitman, Boris Ginsburg
mathjax: true
---

* content
{:toc}

##### Abstract
Batch normalization (BN) has become a de facto standard for training deep convolutional networks. However, BN accounts for a significant fraction of training run-time and is difficult to accelerate, since it is a memory-bandwidth bounded operation. Such a drawback of BN motivates us to explore recently proposed weight normalization algorithms (WN algorithms), i.e. weight normalization, normalization propagation and weight normalization with translated ReLU. These algorithms don't slow-down training iterations and were experimentally shown to outperform BN on relatively small networks and datasets. However, it is not clear if these algorithms could replace BN in practical, large-scale applications. We answer this question by providing a detailed comparison of BN and WN algorithms using ResNet-50 network trained on ImageNet. We found that although WN achieves better training accuracy, the final test accuracy is significantly lower ($\approx 6\%$) than that of BN. This result demonstrates the surprising strength of the BN regularization effect which we were unable to compensate for using standard regularization techniques like dropout and weight decay. We also found that training of deep networks with WN algorithms is significantly less stable compared to BN, limiting their practical applications.

##### Abstract (translated by Google)
批量归一化（BN）已经成为训练深度卷积网络的事实上的标准。然而，由于BN是一个内存带宽有限的操作，所以BN占了训练运行时间的很大一部分，并且很难加速。 BN的这种缺点促使我们探索最近提出的权重归一化算法（WN算法），即权重归一化，归一化传播和具有经翻译的ReLU的权重归一化。这些算法不会减慢训练迭代的速度，并且在相对较小的网络和数据集上实验证明，它们的性能优于国家体育总局。但是，这些算法在实际的大规模应用中是否能取代BN还不清楚。我们通过使用在ImageNet上训练的ResNet-50网络提供BN和WN算法的详细比较来回答这个问题。我们发现虽然WN的训练精度更好，但最终的测试精度要比BN低很多（$ \ approx 6 \％$）。这个结果证明了BN正则化效应令人惊讶的强度，我们无法使用标准正则化技术如辍学和体重衰减来弥补。我们还发现，与BN相比，使用WN算法训练深度网络显着不稳定，限制了它们的实际应用。

##### URL
[https://arxiv.org/abs/1709.08145](https://arxiv.org/abs/1709.08145)

##### PDF
[https://arxiv.org/pdf/1709.08145](https://arxiv.org/pdf/1709.08145)

