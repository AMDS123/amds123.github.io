---
layout: post
title: "YouTube-VOS: Sequence-to-Sequence Video Object Segmentation"
date: 2018-09-03 06:16:13
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation
author: Ning Xu, Linjie Yang, Yuchen Fan, Jianchao Yang, Dingcheng Yue, Yuchen Liang, Brian Price, Scott Cohen, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Learning long-term spatial-temporal features are critical for many video analysis tasks. However, existing video segmentation methods predominantly rely on static image segmentation techniques, and methods capturing temporal dependency for segmentation have to depend on pretrained optical flow models, leading to suboptimal solutions for the problem. End-to-end sequential learning to explore spatial-temporal features for video segmentation is largely limited by the scale of available video segmentation datasets, i.e., even the largest video segmentation dataset only contains 90 short video clips. To solve this problem, we build a new large-scale video object segmentation dataset called YouTube Video Object Segmentation dataset (YouTube-VOS). Our dataset contains 3,252 YouTube video clips and 78 categories including common objects and human activities. This is by far the largest video object segmentation dataset to our knowledge and we have released it at https://youtube-vos.org. Based on this dataset, we propose a novel sequence-to-sequence network to fully exploit long-term spatial-temporal information in videos for segmentation. We demonstrate that our method is able to achieve the best results on our YouTube-VOS test set and comparable results on DAVIS 2016 compared to the current state-of-the-art methods. Experiments show that the large scale dataset is indeed a key factor to the success of our model.

##### Abstract (translated by Google)
学习长期时空特征对于许多视频分析任务至关重要。然而，现有的视频分割方法主要依赖于静态图像分割技术，并且捕获分割的时间依赖性的方法必须依赖于预训练的光流模型，导致该问题的次优解决方案。用于探索视频分割的空间 - 时间特征的端到端顺序学习在很大程度上受可用视频分割数据集的规模限制，即，即使最大的视频分割数据集也仅包含90个短视频剪辑。为了解决这个问题，我们构建了一个名为YouTube视频对象分割数据集（YouTube-VOS）的新的大型视频对象分割数据集。我们的数据集包含3,252个YouTube视频剪辑和78个类别，包括常见对象和人类活动。这是迄今为止我们所知的最大的视频对象分割数据集，我们已经在https://youtube-vos.org上发布了它。基于该数据集，我们提出了一种新颖的序列到序列网络，以充分利用视频中的长期时空信息进行分割。我们证明，与目前最先进的方法相比，我们的方法能够在我们的YouTube-VOS测试集上获得最佳结果，并在DAVIS 2016上获得可比较的结果。实验表明，大规模数据集确实是我们模型成功的关键因素。

##### URL
[http://arxiv.org/abs/1809.00461](http://arxiv.org/abs/1809.00461)

##### PDF
[http://arxiv.org/pdf/1809.00461](http://arxiv.org/pdf/1809.00461)

