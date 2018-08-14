---
layout: post
title: "DFTerNet: Towards 2-bit Dynamic Fusion Networks for Accurate Human Activity Recognition"
date: 2018-07-31 02:33:34
categories: arXiv_AI
tags: arXiv_AI Face CNN Inference Detection Relation Recognition
author: Zhan Yang, Osolo Ian Raymond, ChengYuan Zhang, Ying Wan, Jun Long
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (DCNNs) are currently popular in human activity recognition applications. However, in the face of modern artificial intelligence sensor-based games, many research achievements cannot be practically applied on portable devices. DCNNs are typically resource-intensive and too large to be deployed on portable devices, thus this limits the practical application of complex activity detection. In addition, since portable devices do not possess high-performance Graphic Processing Units (GPUs), there is hardly any improvement in Action Game (ACT) experience. Besides, in order to deal with multi-sensor collaboration, all previous human activity recognition models typically treated the representations from different sensor signal sources equally. However, distinct types of activities should adopt different fusion strategies. In this paper, a novel scheme is proposed. This scheme is used to train 2-bit Convolutional Neural Networks with weights and activations constrained to {-0.5,0,0.5}. It takes into account the correlation between different sensor signal sources and the activity types. This model, which we refer to as DFTerNet, aims at producing a more reliable inference and better trade-offs for practical applications. Our basic idea is to exploit quantization of weights and activations directly in pre-trained filter banks and adopt dynamic fusion strategies for different activity types. Experiments demonstrate that by using dynamic fusion strategy can exceed the baseline model performance by up to ~5% on activity recognition like OPPORTUNITY and PAMAP2 datasets. Using the quantization method proposed, we were able to achieve performances closer to that of full-precision counterpart. These results were also verified using the UniMiB-SHAR dataset. In addition, the proposed method can achieve ~9x acceleration on CPUs and ~11x memory saving.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）目前在人类活动识别应用中很流行。然而，面对现代人工智能传感器游戏，许多研究成果无法实际应用于便携式设备。 DCNN通常是资源密集型的并且太大而不能部署在便携式设备上，因此这限制了复杂活动检测的实际应用。此外，由于便携式设备不具备高性能图形处理单元（GPU），因此动作游戏（ACT）体验几乎没有任何改进。此外，为了处理多传感器协作，所有先前的人类活动识别模型通常同等地处理来自不同传感器信号源的表示。但是，不同类型的活动应采用不同的融合策略。本文提出了一种新的方案。该方案用于训练2位卷积神经网络，其权重和激活约束为{-0.5,0,0.5}。它考虑了不同传感器信号源和活动类型之间的相关性。这个模型，我们称之为DFTerNet，旨在为实际应用提供更可靠的推理和更好的权衡。我们的基本思想是直接在预训练的滤波器组中利用权重和激活的量化，并针对不同的活动类型采用动态融合策略。实验证明，通过使用动态融合策略，可以在活动识别（如OPPORTUNITY和PAMAP2数据集）上超过基线模型性能高达~5％。使用所提出的量化方法，我们能够实现更接近全精度对应物的性能。使用UniMiB-SHAR数据集也验证了这些结果。此外，该方法可以实现CPU的~9倍加速和~11倍的内存节省。

##### URL
[http://arxiv.org/abs/1808.04228](http://arxiv.org/abs/1808.04228)

##### PDF
[http://arxiv.org/pdf/1808.04228](http://arxiv.org/pdf/1808.04228)

