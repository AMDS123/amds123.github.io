---
layout: post
title: "Deep Learning for Precipitation Nowcasting: A Benchmark and A New Model"
date: 2017-10-05 06:31:47
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning
author: Xingjian Shi, Zhihan Gao, Leonard Lausen, Hao Wang, Dit-Yan Yeung, Wai-kin Wong, Wang-chun Woo
mathjax: true
---

* content
{:toc}

##### Abstract
With the goal of making high-resolution forecasts of regional rainfall, precipitation nowcasting has become an important and fundamental technology underlying various public services ranging from rainstorm warnings to flight safety. Recently, the Convolutional LSTM (ConvLSTM) model has been shown to outperform traditional optical flow based methods for precipitation nowcasting, suggesting that deep learning models have a huge potential for solving the problem. However, the convolutional recurrence structure in ConvLSTM-based models is location-invariant while natural motion and transformation (e.g., rotation) are location-variant in general. Furthermore, since deep-learning-based precipitation nowcasting is a newly emerging area, clear evaluation protocols have not yet been established. To address these problems, we propose both a new model and a benchmark for precipitation nowcasting. Specifically, we go beyond ConvLSTM and propose the Trajectory GRU (TrajGRU) model that can actively learn the location-variant structure for recurrent connections. Besides, we provide a benchmark that includes a real-world large-scale dataset from the Hong Kong Observatory, a new training loss, and a comprehensive evaluation protocol to facilitate future research and gauge the state of the art.

##### Abstract (translated by Google)
为了对降水进行高分辨率预报，降水预报成为从暴雨预警到飞行安全等各种公共服务的重要基础技术。最近，卷积LSTM（ConvLSTM）模型已经被证明优于传统的基于光流的降水临近预报方法，这表明深度学习模型具有解决这个问题的巨大潜力。然而，基于ConvLSTM的模型中的卷积递归结构是位置不变的，而自然运动和变换（例如旋转）一般是位置变化的。此外，由于深度学习型降水临近预报是一个新兴的领域，因此尚未建立明确的评估协议。为了解决这些问题，我们提出了降水临近预报的新模式和基准。具体而言，我们超越了ConvLSTM，提出了可以主动学习经常性连接的位置变量结构的Trajectory GRU（TrajGRU）模型。此外，我们提供一个基准，其中包括香港天文台现实世界的大型数据集，新的培训损失和一个综合的评估协议，以方便未来的研究和衡量最新的技术水平。

##### URL
[https://arxiv.org/abs/1706.03458](https://arxiv.org/abs/1706.03458)

##### PDF
[https://arxiv.org/pdf/1706.03458](https://arxiv.org/pdf/1706.03458)

