---
layout: post
title: "Improving Super-Resolution Methods via Incremental Residual Learning"
date: 2018-08-21 20:01:07
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Muneeb Aadil, Rafia Rahim, Sibt ul Hussain
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep Convolutional Neural Networks (CNNs) have shown promising performance in accurate reconstruction of high resolution (HR) image, given its low resolution (LR) counter-part. However, recent state-of-the-art methods operate primarily on LR image for memory efficiency, but we show that it comes at the cost of performance. Furthermore, because spatial dimensions of input and output of such networks do not match, it's not possible to learn residuals in image space; we show that learning residuals in image space leads to performance enhancement. To this end, we propose a novel Incremental Residual Learning (IRL) framework to solve the above mentioned issues. In IRL, a set of branches i.e arbitrary image-to-image networks are trained sequentially where each branch takes spatially upsampled higher dimensional feature maps as input and predicts the residuals of all previous branches combined. We plug recent state of the art methods as base networks in IRL framework and demonstrate the consistent performance enhancement through extensive experiments on public benchmark datasets to set a new state of the art for super-resolution. Compared to the base networks our method incurs no extra memory overhead as only one branch is trained at a time. Furthermore, as our method is trained to learned residuals, complete set of branches are trained in only 20% of time relative to base network.

##### Abstract (translated by Google)
最近，深度卷积神经网络（CNN）已经在高分辨率（HR）图像的精确重建中显示出有希望的性能，因为其具有低分辨率（LR）对应部分。然而，最近最先进的方法主要用于LR图像以提高存储效率，但我们表明它是以性能为代价的。此外，由于这种网络的输入和输出的空间维度不匹配，因此不可能学习图像空间中的残差;我们表明，图像空间中的学习残差会导致性能提升。为此，我们提出了一种新颖的增量残差学习（IRL）框架来解决上述问题。在IRL中，顺序训练一组分支，即任意图像到图像网络，其中每个分支采用空间上采样的高维特征图作为输入，并预测所有先前分支的残差。我们将最新的最先进的方法作为基础网络插入到IRL框架中，并通过对公共基准数据集的大量实验来展示一致的性能增强，以设置超分辨率的新技术水平。与基本网络相比，我们的方法不会产生额外的内存开销，因为一次只训练一个分支。此外，由于我们的方法被训练为学习残差，因此相对于基础网络仅在20％的时间内训练完整的分支集合。

##### URL
[http://arxiv.org/abs/1808.07110](http://arxiv.org/abs/1808.07110)

##### PDF
[http://arxiv.org/pdf/1808.07110](http://arxiv.org/pdf/1808.07110)

