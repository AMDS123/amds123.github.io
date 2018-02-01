---
layout: post
title: "Volumetric Densely Dilated Spatial Pooling ConNets for Prostate Segmentation"
date: 2018-01-31 16:01:36
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Qiuhua Liu, Min Fu, Hao Jiang, Xinqi Gong
mathjax: true
---

* content
{:toc}

##### Abstract
The high incidence rate of prostate disease poses a need in early detection for diagnosis. As one of the main imaging methods used for prostate cancer detection, magnetic resonance imaging (MRI) has wide range in appearance and imbalance problems, making automated prostate segmentation fundamental but challenging we here propose a novel Densely Dilated Spatial Pooling ConNets (DDSP) in encoder-decoder structure. It employs dense structure to combine dilated convolution and global pooling, thus supplies the coarse segmentation results produced by encoder and decoder subnet and preserves more contextual information. To obtain hierarchical feature maps, residual long connection is furtherly adopted to fuse contexture features. Meanwhile, we adopt DSC loss and Jaccard loss functions to train our DDSP network. We surprisingly found and proved that, in contrast to (re-weighted) cross entropy, DSC loss and Jaccard loss have a lot of benign properties in theory, including symmetry, continuity and differentiation about the parameters of network. Extensive experiments on the MICCAI PROMISE12 challenge dataset have been done to corroborate the effectiveness of our DDSP network with DSC loss and Jaccard loss; totally, in test dataset our method achieves a score of 85.78, outperforming most of other competitors.

##### Abstract (translated by Google)
前列腺疾病的高发病率在早期诊断中提出了一个需求。作为用于前列腺癌检测的主要成像方法之一，磁共振成像（MRI）在外观和不平衡问题上具有广泛的范围，使得自动化的前列腺分割成为基础，但是我们在这里提出了一种新颖的密集扩张的空间汇聚连网（DDSP）解码器结构。它采用密集结构将扩张卷积和全局汇聚相结合，从而提供编码器和解码器子网产生的粗分割结果，并保留更多的上下文信息。为了获得分层特征图，进一步采用残差长连接来融合上下文特征。同时，我们采用DSC丢失和Jaccard丢失函数来训练我们的DDSP网络。我们惊奇地发现并证明，与（重新加权的）交叉熵相反，DSC损失和Jaccard损失在理论上具有许多良性性质，包括网络参数的对称性，连续性和差异性。在MICCAI PROMISE12挑战数据集上进行了大量实验，证实了DDSP网络的DSC损失和Jaccard丢失的有效性;总的来说，在测试数据集中，我们的方法得分为85.78，超过了其他大多数竞争对手。

##### URL
[http://arxiv.org/abs/1801.10517](http://arxiv.org/abs/1801.10517)

##### PDF
[http://arxiv.org/pdf/1801.10517](http://arxiv.org/pdf/1801.10517)

