---
layout: post
title: "Pixel Deconvolutional Networks"
date: 2017-11-27 02:53:39
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Relation
author: Hongyang Gao, Hao Yuan, Zhengyang Wang, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Deconvolutional layers have been widely used in a variety of deep models for up-sampling, including encoder-decoder networks for semantic segmentation and deep generative models for unsupervised learning. One of the key limitations of deconvolutional operations is that they result in the so-called checkerboard problem. This is caused by the fact that no direct relationship exists among adjacent pixels on the output feature map. To address this problem, we propose the pixel deconvolutional layer (PixelDCL) to establish direct relationships among adjacent pixels on the up-sampled feature map. Our method is based on a fresh interpretation of the regular deconvolution operation. The resulting PixelDCL can be used to replace any deconvolutional layer in a plug-and-play manner without compromising the fully trainable capabilities of original models. The proposed PixelDCL may result in slight decrease in efficiency, but this can be overcome by an implementation trick. Experimental results on semantic segmentation demonstrate that PixelDCL can consider spatial features such as edges and shapes and yields more accurate segmentation outputs than deconvolutional layers. When used in image generation tasks, our PixelDCL can largely overcome the checkerboard problem suffered by regular deconvolution operations.

##### Abstract (translated by Google)
去卷积层已被广泛用于各种深度上采样模型，包括用于语义分割的编码器 - 解码器网络和用于无监督学习的深度生成模型。去卷积运算的一个关键限制是它们导致了所谓的棋盘格问题。这是由于输出特征映射中相邻像素之间不存在直接关系的事实造成的。为了解决这个问题，我们提出像素去卷积层（PixelDCL）在上采样的特征图上建立相邻像素之间的直接关系。我们的方法基于对常规解卷积操作的新解释。由此产生的PixelDCL可以用来以即插即用的方式替换任何去卷积层，而不会影响原始模型的完全可训练性能。建议的PixelDCL可能会导致效率略有下降，但这可以通过实施技巧来克服。语义分割的实验结果表明，PixelDCL可以考虑诸如边缘和形状的空间特征，并且比去卷积层产生更准确的分割输出。当用于图像生成任务时，我们的PixelDCL可以在很大程度上克服常规反卷积操作所带来的棋盘问题。

##### URL
[https://arxiv.org/abs/1705.06820](https://arxiv.org/abs/1705.06820)

##### PDF
[https://arxiv.org/pdf/1705.06820](https://arxiv.org/pdf/1705.06820)

