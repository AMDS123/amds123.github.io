---
layout: post
title: "Higher-order Pooling of CNN Features via Kernel Linearization for Action Recognition"
date: 2017-01-19 14:30:49
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Deep_Learning Prediction Relation Recognition
author: Anoop Cherian, Piotr Koniusz, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Most successful deep learning algorithms for action recognition extend models designed for image-based tasks such as object recognition to video. Such extensions are typically trained for actions on single video frames or very short clips, and then their predictions from sliding-windows over the video sequence are pooled for recognizing the action at the sequence level. Usually this pooling step uses the first-order statistics of frame-level action predictions. In this paper, we explore the advantages of using higher-order correlations; specifically, we introduce Higher-order Kernel (HOK) descriptors generated from the late fusion of CNN classifier scores from all the frames in a sequence. To generate these descriptors, we use the idea of kernel linearization. Specifically, a similarity kernel matrix, which captures the temporal evolution of deep classifier scores, is first linearized into kernel feature maps. The HOK descriptors are then generated from the higher-order co-occurrences of these feature maps, and are then used as input to a video-level classifier. We provide experiments on two fine-grained action recognition datasets and show that our scheme leads to state-of-the-art results.

##### Abstract (translated by Google)
大多数成功的动作识别深度学习算法扩展了为基于图像的任务设计的模型，如对象识别到视频。这种扩展通常是针对单个视频帧或非常短的剪辑进行训练，然后从视频序列上的滑动窗口预测其集合以识别序列级别的动作。通常这个池化步骤使用帧级动作预测的一阶统计。在本文中，我们探讨使用高阶相关的优点;具体来说，我们引入由序列中所有帧的CNN分类器得分的后期融合产生的高阶核（HOK）描述符。为了生成这些描述符，我们使用核线性化的思想。具体来说，捕获深度分类器得分的时间演化的相似性核矩阵首先线性化为核函数图。然后，HOK描述符从这些特征映射的高阶共现中生成，然后用作视频级分类器的输入。我们提供了两个细粒度动作识别数据集的实验，并显示我们的方案导致了最先进的结果。

##### URL
[https://arxiv.org/abs/1701.05432](https://arxiv.org/abs/1701.05432)

##### PDF
[https://arxiv.org/pdf/1701.05432](https://arxiv.org/pdf/1701.05432)

