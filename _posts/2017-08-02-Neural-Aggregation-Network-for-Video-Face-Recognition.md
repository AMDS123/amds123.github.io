---
layout: post
title: "Neural Aggregation Network for Video Face Recognition"
date: 2017-08-02 08:08:14
categories: arXiv_CV
tags: arXiv_CV Attention Face Embedding CNN Classification Recognition Face_Recognition
author: Jiaolong Yang, Peiran Ren, Dongqing Zhang, Dong Chen, Fang Wen, Hongdong Li, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a Neural Aggregation Network (NAN) for video face recognition. The network takes a face video or face image set of a person with a variable number of face images as its input, and produces a compact, fixed-dimension feature representation for recognition. The whole network is composed of two modules. The feature embedding module is a deep Convolutional Neural Network (CNN) which maps each face image to a feature vector. The aggregation module consists of two attention blocks which adaptively aggregate the feature vectors to form a single feature inside the convex hull spanned by them. Due to the attention mechanism, the aggregation is invariant to the image order. Our NAN is trained with a standard classification or verification loss without any extra supervision signal, and we found that it automatically learns to advocate high-quality face images while repelling low-quality ones such as blurred, occluded and improperly exposed faces. The experiments on IJB-A, YouTube Face, Celebrity-1000 video face recognition benchmarks show that it consistently outperforms naive aggregation methods and achieves the state-of-the-art accuracy.

##### Abstract (translated by Google)
本文提出了一种用于视频人脸识别的神经聚合网络（NAN）。该网络将具有可变数量的人脸图像的人的脸部视频或人脸图像集合作为其输入，并且产生用于识别的紧凑的，固定维度的特征表示。整个网络由两个模块组成。特征嵌入模块是深度卷积神经网络（CNN），其将每个人脸图像映射到特征向量。聚合模块由两个注意块组成，这两个注意块自适应地聚合特征向量以在它们所跨越的凸包内部形成单个特征。由于注意机制，聚合对于图像顺序是不变的。我们的NAN是在没有任何额外的监督信号的情况下训练的标准分类或验证损失，我们发现它自动学习提倡高质量的脸部图像，同时排斥低质量的脸部图像，如模糊，遮挡和不正确的脸部。在IJB-A，YouTube Face，Celebrity-1000视频人脸识别基准上进行的实验表明，它始终超越幼稚的聚合方法，并达到了最新的精确度。

##### URL
[https://arxiv.org/abs/1603.05474](https://arxiv.org/abs/1603.05474)

##### PDF
[https://arxiv.org/pdf/1603.05474](https://arxiv.org/pdf/1603.05474)

