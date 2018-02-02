---
layout: post
title: "Densely Dilated Spatial Pooling Convolutional Network using benign loss functions for imbalanced volumetric prostate segmentation"
date: 2018-02-01 11:41:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Qiuhua Liu, Min Fu, Xinqi Gong, Hao Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
The high incidence rate of prostate disease poses a requirement in early detection for diagnosis. As one of the main imaging methods used for prostate cancer detection, Magnetic Resonance Imaging (MRI) has wide range of appearance and imbalance problems, making automated prostate segmentation fundamental but challenging. Here we propose a novel Densely Dilated Spatial Pooling Convolutional Network (DDSP ConNet) in encoder-decoder structure. It employs dense structure to combine dilated convolution and global pooling, thus supplies coarse segmentation results from encoder and decoder subnet and preserves more contextual information. To obtain richer hierarchical feature maps, residual long connection is furtherly adopted to fuse contexture features. Meanwhile, we adopt DSC loss and Jaccard loss functions to train our DDSP ConNet. We surprisingly found and proved that, in contrast to re-weighted cross entropy, DSC loss and Jaccard loss have a lot of benign properties in theory, including symmetry, continuity and differentiability about the parameters of network. Extensive experiments on the MICCAI PROMISE12 challenge dataset have been done to corroborate the effectiveness of our DDSP ConNet with DSC loss and Jaccard loss. Totally, our method achieves a score of 85.78 in the test dataset, outperforming most of other competitors.

##### Abstract (translated by Google)
前列腺疾病的高发病率对早期发现诊断提出了要求。作为用于前列腺癌检测的主要成像方法之一，磁共振成像（MRI）具有广泛的外观和不平衡问题，使得自动化的前列腺分割成为基本但是具有挑战性的问题。在这里我们提出了一种新颖的密集扩展的空间池卷积网络（DDSP ConNet）编码器 - 解码器结构。它采用密集结构将扩张卷积和全局汇聚相结合，从编码器和解码器子网提供粗分割结果，保留更多的上下文信息。为了获得更丰富的分层特征图，进一步采用剩余长连接来融合上下文特征。同时，我们采用DSC丢失和Jaccard丢失函数来训练我们的DDSP ConNet。我们惊奇地发现和证明了，与重新加权的交叉熵相反，DSC损失和Jaccard损失在理论上具有很多良性，包括网络参数的对称性，连续性和可微性。在MICCAI PROMISE12挑战数据集上进行了大量实验，证实了我们DDSP ConNet的有效性，其中DSC丢失和Jaccard丢失。总的来说，我们的方法在测试数据集中获得了85.78的分数，超越了其他大多数竞争对手。

##### URL
[http://arxiv.org/abs/1801.10517](http://arxiv.org/abs/1801.10517)

##### PDF
[http://arxiv.org/pdf/1801.10517](http://arxiv.org/pdf/1801.10517)

