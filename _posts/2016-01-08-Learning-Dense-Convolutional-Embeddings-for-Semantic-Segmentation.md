---
layout: post
title: "Learning Dense Convolutional Embeddings for Semantic Segmentation"
date: 2016-01-08 01:16:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Semantic_Segmentation Classification Deep_Learning
author: Adam W. Harley, Konstantinos G. Derpanis, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new deep convolutional neural network (DCNN) architecture that learns pixel embeddings, such that pairwise distances between the embeddings can be used to infer whether or not the pixels lie on the same region. That is, for any two pixels on the same object, the embeddings are trained to be similar; for any pair that straddles an object boundary, the embeddings are trained to be dissimilar. Experimental results show that when this embedding network is used in conjunction with a DCNN trained on semantic segmentation, there is a systematic improvement in per-pixel classification accuracy. Our contributions are integrated in the popular Caffe deep learning framework, and consist in straightforward modifications to convolution routines. As such, they can be exploited for any task involving convolution layers.

##### Abstract (translated by Google)
本文提出了一种新的深度卷积神经网络（DCNN）架构来学习像素嵌入，使得嵌入之间的成对距离可以用来推断像素是否位于同一个区域。也就是说，对于同一对象上的任何两个像素，嵌入被训练成相似的;对于跨越对象边界的任何对，嵌入被训练成不相似的。实验结果表明，当这种嵌入网络与语义分割训练的DCNN结合使用时，每个像素的分类精度有了系统的改善。我们的贡献集成在流行的Caffe深度学习框架中，并对卷积程序进行直接修改。因此，它们可以用于任何涉及卷积层的任务。

##### URL
[https://arxiv.org/abs/1511.04377](https://arxiv.org/abs/1511.04377)

##### PDF
[https://arxiv.org/pdf/1511.04377](https://arxiv.org/pdf/1511.04377)

