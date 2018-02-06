---
layout: post
title: "Large-Scale Image Retrieval with Attentive Deep Local Features"
date: 2018-02-03 02:19:16
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Attention CNN Detection
author: Hyeonwoo Noh, Andre Araujo, Jack Sim, Tobias Weyand, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an attentive local feature descriptor suitable for large-scale image retrieval, referred to as DELF (DEep Local Feature). The new feature is based on convolutional neural networks, which are trained only with image-level annotations on a landmark image dataset. To identify semantically useful local features for image retrieval, we also propose an attention mechanism for keypoint selection, which shares most network layers with the descriptor. This framework can be used for image retrieval as a drop-in replacement for other keypoint detectors and descriptors, enabling more accurate feature matching and geometric verification. Our system produces reliable confidence scores to reject false positives---in particular, it is robust against queries that have no correct match in the database. To evaluate the proposed descriptor, we introduce a new large-scale dataset, referred to as Google-Landmarks dataset, which involves challenges in both database and query such as background clutter, partial occlusion, multiple landmarks, objects in variable scales, etc. We show that DELF outperforms the state-of-the-art global and local descriptors in the large-scale setting by significant margins. Code and dataset can be found at the project webpage: https://github.com/tensorflow/models/tree/master/research/delf .

##### Abstract (translated by Google)
我们提出了一个适合于大规模图像检索的专注的局部特征描述符，称为DELF（DEep Local Feature）。新功能基于卷积神经网络，仅在地标图像数据集上使用图像级注释进行训练。为了识别用于图像检索的语义上有用的局部特征，我们还提出了关键点选择的关注机制，其与描述符共享大多数网络层。该框架可用于图像检索，作为其他关键点检测器和描述符的直接替换，从而实现更精确的特征匹配和几何验证。我们的系统生成可靠的置信度分数来拒绝误报 - 特别是对于在数据库中没有正确匹配的查询，它是可靠的。为了评估提出的描述符，我们引入了一个新的大规模数据集，称为Google-Landmarks数据集，它涉及数据库和查询方面的挑战，如背景杂波，局部遮挡，多标记，变尺度对象等。表明DELF在大规模环境中的表现优于最先进的全球和地方描述符。代码和数据集可以在项目网页上找到：https：//github.com/tensorflow/models/tree/master/research/delf。

##### URL
[http://arxiv.org/abs/1612.06321](http://arxiv.org/abs/1612.06321)

##### PDF
[http://arxiv.org/pdf/1612.06321](http://arxiv.org/pdf/1612.06321)

