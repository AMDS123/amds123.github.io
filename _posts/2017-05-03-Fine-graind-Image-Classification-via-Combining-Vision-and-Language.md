---
layout: post
title: "Fine-graind Image Classification via Combining Vision and Language"
date: 2017-05-03 03:01:38
categories: arXiv_CV
tags: arXiv_CV Salient CNN Image_Classification Classification Detection
author: Xiangteng He, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained image classification is a challenging task due to the large intra-class variance and small inter-class variance, aiming at recognizing hundreds of sub-categories belonging to the same basic-level category. Most existing fine-grained image classification methods generally learn part detection models to obtain the semantic parts for better classification accuracy. Despite achieving promising results, these methods mainly have two limitations: (1) not all the parts which obtained through the part detection models are beneficial and indispensable for classification, and (2) fine-grained image classification requires more detailed visual descriptions which could not be provided by the part locations or attribute annotations. For addressing the above two limitations, this paper proposes the two-stream model combining vision and language (CVL) for learning latent semantic representations. The vision stream learns deep representations from the original visual information via deep convolutional neural network. The language stream utilizes the natural language descriptions which could point out the discriminative parts or characteristics for each image, and provides a flexible and compact way of encoding the salient visual aspects for distinguishing sub-categories. Since the two streams are complementary, combining the two streams can further achieves better classification accuracy. Comparing with 12 state-of-the-art methods on the widely used CUB-200-2011 dataset for fine-grained image classification, the experimental results demonstrate our CVL approach achieves the best performance.

##### Abstract (translated by Google)
细粒度图像分类是一个具有挑战性的任务，因为类内差异大，类间差异小，旨在识别属于同一基本类别的数百个子类别。大多数现有的细粒度图像分类方法一般都是学习部分检测模型来获取语义部分，以提高分类精度。尽管取得了可喜的成果，但这些方法主要有两个局限性：（1）通过零件检测模型获得的所有零件不是所有的分类都是有益和不可或缺的;（2）细粒度的图像分类需要更详细的视觉描述，由零件位置或属性注释提供。为了解决上述两个局限性，本文提出了将视觉和语言（CVL）相结合的双流模型来学习潜在的语义表征。视觉流通过深度卷积神经网络从原始视觉信息中学习深度表示。语言流利用自然语言描述，可以指出每个图像的判别性部分或特征，并提供一种灵活而紧凑的方式来编码突出的视觉方面以区分子类别。由于这两个流是互补的，所以组合这两个流可以进一步实现更好的分类精度。与广泛使用的CUB-200-2011数据集中的12种最先进的方法相比，用于细粒度图像分类的实验结果证明了我们的CVL方法达到最佳性能。

##### URL
[https://arxiv.org/abs/1704.02792](https://arxiv.org/abs/1704.02792)

##### PDF
[https://arxiv.org/pdf/1704.02792](https://arxiv.org/pdf/1704.02792)

