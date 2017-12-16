---
layout: post
title: "Superpixel-based Semantic Segmentation Trained by Statistical Process Control"
date: 2017-08-07 10:35:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Hyojin Park, Jisoo Jeong, Youngjoon Yoo, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation, like other fields of computer vision, has seen a remarkable performance advance by the use of deep convolution neural networks. However, considering that neighboring pixels are heavily dependent on each other, both learning and testing of these methods have a lot of redundant operations. To resolve this problem, the proposed network is trained and tested with only 0.37% of total pixels by superpixel-based sampling and largely reduced the complexity of upsampling calculation. The hypercolumn feature maps are constructed by pyramid module in combination with the convolution layers of the base network. Since the proposed method uses a very small number of sampled pixels, the end-to-end learning of the entire network is difficult with a common learning rate for all the layers. In order to resolve this problem, the learning rate after sampling is controlled by statistical process control (SPC) of gradients in each layer. The proposed method performs better than or equal to the conventional methods that use much more samples on Pascal Context, SUN-RGBD dataset.

##### Abstract (translated by Google)
与其他计算机视觉领域一样，语义分割通过使用深度卷积神经网络已经看到了显着的性能提升。然而，考虑到相邻像素彼此严重依赖，这些方法的学习和测试都有很多冗余操作。为了解决这个问题，所提出的网络通过基于超像素的采样仅用总像素的0.37％进行训练和测试，并大大降低了上采样计算的复杂度。超柱特征图由金字塔模块与基础网络的卷积层相结合构成。由于所提出的方法使用了非常少量的采样像素，因此对于所有层而言，整个网络的端到端学习是困难的，并且具有共同的学习速率。为了解决这个问题，采样后的学习率由每层梯度的统计过程控制（SPC）来控制。所提出的方法执行比在Pascal上下文，SUN-RGBD数据集上使用更多样本的传统​​方法更好或者相等。

##### URL
[https://arxiv.org/abs/1706.10071](https://arxiv.org/abs/1706.10071)

##### PDF
[https://arxiv.org/pdf/1706.10071](https://arxiv.org/pdf/1706.10071)

