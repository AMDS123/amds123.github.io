---
layout: post
title: "Hierarchical Deep Recurrent Architecture for Video Understanding"
date: 2017-07-11 14:25:16
categories: arXiv_CV
tags: arXiv_CV Video_Caption Attention Video_Classification RNN Classification
author: Luming Tang, Boyang Deng, Haiyu Zhao, Shuai Yi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the system we developed for the Youtube-8M Video Understanding Challenge, in which a large-scale benchmark dataset was used for multi-label video classification. The proposed framework contains hierarchical deep architecture, including the frame-level sequence modeling part and the video-level classification part. In the frame-level sequence modelling part, we explore a set of methods including Pooling-LSTM (PLSTM), Hierarchical-LSTM (HLSTM), Random-LSTM (RLSTM) in order to address the problem of large amount of frames in a video. We also introduce two attention pooling methods, single attention pooling (ATT) and multiply attention pooling (Multi-ATT) so that we can pay more attention to the informative frames in a video and ignore the useless frames. In the video-level classification part, two methods are proposed to increase the classification performance, i.e. Hierarchical-Mixture-of-Experts (HMoE) and Classifier Chains (CC). Our final submission is an ensemble consisting of 18 sub-models. In terms of the official evaluation metric Global Average Precision (GAP) at 20, our best submission achieves 0.84346 on the public 50% of test dataset and 0.84333 on the private 50% of test data.

##### Abstract (translated by Google)
本文介绍了我们针对Youtube-8M视频理解挑战而开发的系统，其中大规模基准数据集被用于多标签视频分类。提出的框架包含层次深层架构，包括帧级序列建模部分和视频级分类部分。在帧级序列建模部分，我们研究了一系列的方法，包括Pooling-LSTM（PLSTM），Hierarchical-LSTM（HLSTM），Random-LSTM（RLSTM），以解决视频中大量帧的问题。我们还引入了单注意池（ATT）和多注意池（Multi-ATT）两种注意力集中方法，以便更多地关注视频中的信息帧，忽略无用的帧。在视频级别分类部分中，提出了两种方法来提高分类性能，即分层专家混合（HMoE）和分类器链（CC）。我们最后提交的是一个由18个子模型组成的合奏。根据20日的官方评估指标“全球平均精度（GAP）”，我们最好的提交数据在公开测试数据集的50％上达到了0.84346，而在私有测试数据的50％上达到了0.84333。

##### URL
[https://arxiv.org/abs/1707.03296](https://arxiv.org/abs/1707.03296)

##### PDF
[https://arxiv.org/pdf/1707.03296](https://arxiv.org/pdf/1707.03296)

