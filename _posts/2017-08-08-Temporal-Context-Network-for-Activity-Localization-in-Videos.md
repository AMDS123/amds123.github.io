---
layout: post
title: "Temporal Context Network for Activity Localization in Videos"
date: 2017-08-08 01:46:03
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Xiyang Dai, Bharat Singh, Guyue Zhang, Larry S. Davis, Yan Qiu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Temporal Context Network (TCN) for precise temporal localization of human activities. Similar to the Faster-RCNN architecture, proposals are placed at equal intervals in a video which span multiple temporal scales. We propose a novel representation for ranking these proposals. Since pooling features only inside a segment is not sufficient to predict activity boundaries, we construct a representation which explicitly captures context around a proposal for ranking it. For each temporal segment inside a proposal, features are uniformly sampled at a pair of scales and are input to a temporal convolutional neural network for classification. After ranking proposals, non-maximum suppression is applied and classification is performed to obtain final detections. TCN outperforms state-of-the-art methods on the ActivityNet dataset and the THUMOS14 dataset.

##### Abstract (translated by Google)
我们提出一个时间上下文网络（TCN）精确时间本地化的人类活动。类似于Faster-RCNN体系结构，提案以等间隔放置在跨越多个时间尺度的视频中。我们提出了一个新的表示方法来排列这些提议由于仅在一个细分市场中汇集特征不足以预测活动边界，所以我们构建了一个表示，该表示明确地捕获了对该细分进行排序的提案的上下文。对于提案内的每个时间段，特征在一对尺度上均匀采样，并被输入到时间卷积神经网络用于分类。排序建议后，应用非最大抑制，并进行分类以获得最终检测结果。 TCN优于ActivityNet数据集和THUMOS14数据集的最新方法。

##### URL
[https://arxiv.org/abs/1708.02349](https://arxiv.org/abs/1708.02349)

##### PDF
[https://arxiv.org/pdf/1708.02349](https://arxiv.org/pdf/1708.02349)

