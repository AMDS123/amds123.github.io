---
layout: post
title: "Efficient Deep Aesthetic Image Classification using Connected Local and Global Features"
date: 2017-08-17 02:23:09
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Xin Jin, Le Wu, Zheyuan He, Siyu Chen, Jingying Chi, Siwei Peng, Xiaodong Li, Shiming Ge
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate the aesthetic image classification problem, also known as automatically classifying an image into low or high aesthetic quality, which is quite a challenging problem. Considering both the local and global information of images is quite important for image aesthetic quality assessment. Currently, a powerful inception module is proposed which shows very high performance in object classification. We have the observation that the inception module has the ability of considering both the local and global features in nature. Thus, in this paper, we propose a novel DCNN structure codenamed ILGNet for image aesthetics classification, which introduces the Inception module and connects intermediate Local layers to the Global layer for the output. In addition, the ILGNet is derived from part of the GoogLeNet. Thus, we can easily use a pre-trained image classification GoogleLeNet model on the ImageNet dataset and fine tune our connected local and global layer on the large scale aesthetics assessment AVA dataset. The experimental results show that the proposed ILGNet outperforms the state of the art results in image aesthetics assessment in the AVA benchmark. The time cost of both training and test of the ILGNet are significantly less than those of full GoogLeNet with only a little reduction of the classification accuracy. Our ILGNet can achieve similar classification accuracy as that of 2/3 GoogLeNet, whose computational cost is nearly twice of ours. This makes the aesthetic assessment model more easily to be integrated into mobile and embedded systems.

##### Abstract (translated by Google)
在本文中，我们调查审美图像分类问题，也被称为自动分类低或高审美质量的图像，这是一个相当具有挑战性的问题。考虑到图像的局部和全局信息对于图像美学质量评估是非常重要的。目前，提出了一个功能强大的初始模块，在对象分类中表现出了很高的性能。我们有观察到，初始模块有能力兼顾本地和全球的特点。因此，本文提出了一种新的DCNN结构，代号为ILGNet，用于图像美学分类，引入了Inception模块，并将中间Local层连接到Global层进行输出。另外，ILGNet来源于GoogLeNet的一部分。因此，我们可以很容易地在ImageNet数据集上使用预先训练的图像分类GoogleLeNet模型，并在大规模美学评估AVA数据集上微调我们连接的本地和全球层。实验结果表明，所提出的ILGNet在AVA基准测试中胜过了最先进的图像美学评估结果。 ILGNet的培训和测试的时间成本显着低于完整的GoogLeNet，而分类准确度只有少许降低。我们的ILGNet可以达到与2/3 GoogLeNet类似的分类精度，其计算成本几乎是我们的两倍。这使得审美评估模型更容易被集成到移动和嵌入式系统中。

##### URL
[https://arxiv.org/abs/1610.02256](https://arxiv.org/abs/1610.02256)

##### PDF
[https://arxiv.org/pdf/1610.02256](https://arxiv.org/pdf/1610.02256)

