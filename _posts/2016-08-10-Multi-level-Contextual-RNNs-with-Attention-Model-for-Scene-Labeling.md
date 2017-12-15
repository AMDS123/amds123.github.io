---
layout: post
title: "Multi-level Contextual RNNs with Attention Model for Scene Labeling"
date: 2016-08-10 21:15:51
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference RNN Relation
author: Heng Fan, Xue Mei, Danil Prokhorov, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Context in image is crucial for scene labeling while existing methods only exploit local context generated from a small surrounding area of an image patch or a pixel, by contrast long-range and global contextual information is ignored. To handle this issue, we in this work propose a novel approach for scene labeling by exploring multi-level contextual recurrent neural networks (ML-CRNNs). Specifically, we encode three kinds of contextual cues, i.e., local context, global context and image topic context in structural recurrent neural networks (RNNs) to model long-range local and global dependencies in image. In this way, our method is able to `see' the image in terms of both long-range local and holistic views, and make a more reliable inference for image labeling. Besides, we integrate the proposed contextual RNNs into hierarchical convolutional neural networks (CNNs), and exploit dependence relationships in multiple levels to provide rich spatial and semantic information. Moreover, we novelly adopt an attention model to effectively merge multiple levels and show that it outperforms average- or max-pooling fusion strategies. Extensive experiments demonstrate that the proposed approach achieves new state-of-the-art results on the CamVid, SiftFlow and Stanford-background datasets.

##### Abstract (translated by Google)
图像中的上下文对于场景标记是至关重要的，而现有的方法仅利用从图像块或像素的小周围区域生成的本地上下文，相比之下，远程和全局上下文信息被忽略。为了解决这个问题，我们在这个工作中提出了一个新的方法来探索多层次的上下文递归神经网络（ML-CRNNs）。具体而言，我们对结构递归神经网络（RNN）中的三种上下文线索（即局部上下文，全局上下文和图像话题上下文）进行编码，以对图像中的长距离局部和全局依赖性进行建模。这样，我们的方法就能够以远距离的局部和整体的观点来“看”图像，并且为图像标记做出更可靠的推断。此外，将提出的上下文RNN集成到分层卷积神经网络（CNN）中，利用多层次依赖关系提供丰富的空间和语义信息。此外，我们新颖地采用了一个关注模型来有效地融合多个层次，并且表现出它优于平均或最大融合策略。大量实验表明，所提出的方法在CamVid，SiftFlow和Stanford背景数据集上实现了最新的最新成果。

##### URL
[https://arxiv.org/abs/1607.02537](https://arxiv.org/abs/1607.02537)

##### PDF
[https://arxiv.org/pdf/1607.02537](https://arxiv.org/pdf/1607.02537)

