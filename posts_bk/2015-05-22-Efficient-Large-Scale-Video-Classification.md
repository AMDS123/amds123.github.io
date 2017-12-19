---
layout: post
title: "Efficient Large Scale Video Classification"
date: 2015-05-22 23:45:32
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Video_Classification Classification
author: Balakrishnan Varadarajan, George Toderici, Sudheendra Vijayanarasimhan, Apostol Natsev
mathjax: true
---

* content
{:toc}

##### Abstract
Video classification has advanced tremendously over the recent years. A large part of the improvements in video classification had to do with the work done by the image classification community and the use of deep convolutional networks (CNNs) which produce competitive results with hand- crafted motion features. These networks were adapted to use video frames in various ways and have yielded state of the art classification results. We present two methods that build on this work, and scale it up to work with millions of videos and hundreds of thousands of classes while maintaining a low computational cost. In the context of large scale video processing, training CNNs on video frames is extremely time consuming, due to the large number of frames involved. We propose to avoid this problem by training CNNs on either YouTube thumbnails or Flickr images, and then using these networks' outputs as features for other higher level classifiers. We discuss the challenges of achieving this and propose two models for frame-level and video-level classification. The first is a highly efficient mixture of experts while the latter is based on long short term memory neural networks. We present results on the Sports-1M video dataset (1 million videos, 487 classes) and on a new dataset which has 12 million videos and 150,000 labels.

##### Abstract (translated by Google)
视频分类近年来已经取得了巨大的进步。视频分类方面的很大一部分改进与图像分类社区所做的工作以及使用深度卷积网络（CNN）相结合，这些网络通过手工制作的运动特征产生了有竞争力的结果。这些网络适合于以各种方式使用视频帧，并已经产生了最新的分类结果。我们提出了基于这项工作的两种方法，并将其扩展到与数百万个视频和数十万个类一起工作，同时保持低计算成本。在大规模视频处理的情况下，由于涉及大量的帧，训练视频帧上的CNN是非常耗时的。我们建议通过在YouTube缩略图或Flickr图像上训练CNN来避免这个问题，然后将这些网络的输出用作其他更高级分类器的特征。我们讨论实现这一目标的挑战，并提出两种框架级和视频级分类模型。首先是专家的高效率混合，而后者是基于长期的短期记忆神经网络。我们在Sports-1M视频数据集（100万个视频，487个课程）和一个拥有1200万个视频和15万个标签的新数据集上提供结果。

##### URL
[https://arxiv.org/abs/1505.06250](https://arxiv.org/abs/1505.06250)

##### PDF
[https://arxiv.org/pdf/1505.06250](https://arxiv.org/pdf/1505.06250)

