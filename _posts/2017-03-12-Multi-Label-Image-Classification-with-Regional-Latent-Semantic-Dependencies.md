---
layout: post
title: "Multi-Label Image Classification with Regional Latent Semantic Dependencies"
date: 2017-03-12 23:41:23
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification RNN Classification
author: Junjie Zhang, Qi Wu, Chunhua Shen, Jian Zhang, Jianfeng Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolution neural networks (CNN) have demonstrated advanced performance on single-label image classification, and various progress also have been made to apply CNN methods on multi-label image classification, which requires to annotate objects, attributes, scene categories etc. in a single shot. Recent state-of-the-art approaches to multi-label image classification exploit the label dependencies in an image, at global level, largely improving the labeling capacity. However, predicting small objects and visual concepts is still challenging due to the limited discrimination of the global visual features. In this paper, we propose a Regional Latent Semantic Dependencies model (RLSD) to address this problem. The utilized model includes a fully convolutional localization architecture to localize the regions that may contain multiple highly-dependent labels. The localized regions are further sent to the recurrent neural networks (RNN) to characterize the latent semantic dependencies at the regional level. Experimental results on several benchmark datasets show that our proposed model achieves the best performance compared to the state-of-the-art models, especially for predicting small objects occurred in the images. In addition, we set up an upper bound model (RLSD+ft-RPN) using bounding box coordinates during training, the experimental results also show that our RLSD can approach the upper bound without using the bounding-box annotations, which is more realistic in the real world.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）在单标签图像分类上表现出了先进的性能，CNN方法在多标签图像分类方面也取得了不同的进展，需要在对标签进行标注的时候需要注解对象，属性，场景类别等单发。最近用于多标签图像分类的最新技术方法在全球范围内利用图像中的标签依赖性，极大地提高了标签容量。然而，由于对全球视觉特征的有限区分，预测小物体和视觉概念仍然具​​有挑战性。在本文中，我们提出了区域潜在语义依赖模型（RLSD）来解决这个问题。所使用的模型包括完全卷积定位体系结构以定位可能包含多个高度依赖标签的区域。局部区域被进一步发送到递归神经网络（RNN）以表征区域级别的潜在语义依赖性。在几个基准数据集上的实验结果表明，我们提出的模型与现有技术的模型相比，达到了最好的性能，特别是预测图像中出现的小物体。另外，在训练过程中利用边界框坐标建立了上界模型（RLSD + ft-RPN），实验结果也表明，我们的RLSD能够在不使用边界框注解的情况下逼近上界，现实世界。

##### URL
[https://arxiv.org/abs/1612.01082](https://arxiv.org/abs/1612.01082)

##### PDF
[https://arxiv.org/pdf/1612.01082](https://arxiv.org/pdf/1612.01082)

