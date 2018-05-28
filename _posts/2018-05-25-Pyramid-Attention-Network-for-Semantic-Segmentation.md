---
layout: post
title: "Pyramid Attention Network for Semantic Segmentation"
date: 2018-05-25 14:40:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation
author: Hanchao Li, Pengfei Xiong, Jie An, Lingxue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
A Pyramid Attention Network(PAN) is proposed to exploit the impact of global contextual information in semantic segmentation. Different from most existing works, we combine attention mechanism and spatial pyramid to extract precise dense features for pixel labeling instead of complicated dilated convolution and artificially designed decoder networks. Specifically, we introduce a Feature Pyramid Attention module to perform spatial pyramid attention structure on high-level output and combining global pooling to learn a better feature representation, and a Global Attention Upsample module on each decoder layer to provide global context as a guidance of low-level features to select category localization details. The proposed approach achieves state-of-the-art performance on PASCAL VOC 2012 and Cityscapes benchmarks with a new record of mIoU accuracy 84.0% on PASCAL VOC 2012, while training without COCO dataset.

##### Abstract (translated by Google)
金字塔注意网络（PAN）被提出来利用全球语境信息在语义分割中的影响。与大多数现有的作品不同，我们结合注意机制和空间金字塔来提取精确的像素标记密集特征，而不是复杂的扩张卷积和人为设计的解码器网络。具体来说，我们引入了特征金字塔注意模块来对高层输出执行空间金字塔注意结构，并将全局池合并以学习更好的特征表示，并在每个解码器层上提供全局注意上升模块以提供全局上下文作为低级别的功能来选择类别本地化的细节。该提议的方法在PASCAL VOC 2012和Cityscapes基准测试中实现了最新的性能，在PASCAL VOC 2012上新记录的mIoU准确率为84.0％，而没有COCO数据集的训练。

##### URL
[http://arxiv.org/abs/1805.10180](http://arxiv.org/abs/1805.10180)

##### PDF
[http://arxiv.org/pdf/1805.10180](http://arxiv.org/pdf/1805.10180)

