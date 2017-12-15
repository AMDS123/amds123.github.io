---
layout: post
title: "Modeling Spatial and Temporal Cues for Multi-label Facial Action Unit Detection"
date: 2016-08-02 17:37:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN RNN Prediction Detection Relation
author: Wen-Sheng Chu, Fernando De la Torre, Jeffrey F. Cohn
mathjax: true
---

* content
{:toc}

##### Abstract
Facial action units (AUs) are essential to decode human facial expressions. Researchers have focused on training AU detectors with a variety of features and classifiers. However, several issues remain. These are spatial representation, temporal modeling, and AU correlation. Unlike most studies that tackle these issues separately, we propose a hybrid network architecture to jointly address them. Specifically, spatial representations are extracted by a Convolutional Neural Network (CNN), which, as analyzed in this paper, is able to reduce person-specific biases caused by hand-crafted features (eg, SIFT and Gabor). To model temporal dependencies, Long Short-Term Memory (LSTMs) are stacked on top of these representations, regardless of the lengths of input videos. The outputs of CNNs and LSTMs are further aggregated into a fusion network to produce per-frame predictions of 12 AUs. Our network naturally addresses the three issues, and leads to superior performance compared to existing methods that consider these issues independently. Extensive experiments were conducted on two large spontaneous datasets, GFT and BP4D, containing more than 400,000 frames coded with 12 AUs. On both datasets, we report significant improvement over a standard multi-label CNN and feature-based state-of-the-art. Finally, we provide visualization of the learned AU models, which, to our best knowledge, reveal how machines see facial AUs for the first time.

##### Abstract (translated by Google)
脸部动作单元（AU）对于解码人脸表情是至关重要的。研究人员专注于训练具有各种特征和分类器的所有检测器。但是，仍有几个问题。这些是空间表示，时间建模和AU关联。与大多数单独解决这些问题的研究不同，我们提出了混合网络架构来共同解决这些问题。具体而言，空间表示是由卷积神经网络（CNN）提取的，如本文所分析的，能够减少由手工特征（例如SIFT和Gabor）引起的特定人的偏差。为了对时间依赖性建模，无论输入视频的长度如何，长期短期记忆（LSTM）都堆叠在这些表示之上。将CNN和LSTM的输出进一步聚合成融合网络，以产生12个AU的每帧预测。我们的网络自然解决了这三个问题，并且与现有的独立考虑这些问题的方法相比，性能更优越。对两个大的自发数据集GFT和BP4D进行了大量的实验，其中包含用12个AU编码的400,000个以上的帧。在这两个数据集上，我们报告了标准多标签CNN和基于特征的最新技术的显着改进。最后，我们提供了学习的AU模型的可视化，据我们所知，这是第一次揭示机器如何看待面部AU。

##### URL
[https://arxiv.org/abs/1608.00911](https://arxiv.org/abs/1608.00911)

##### PDF
[https://arxiv.org/pdf/1608.00911](https://arxiv.org/pdf/1608.00911)

