---
layout: post
title: "ContextVP: Fully Context-Aware Video Prediction"
date: 2018-05-14 01:18:16
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction
author: Wonmin Byeon, Qin Wang, Rupesh Kumar Srivastava, Petros Koumoutsakos
mathjax: true
---

* content
{:toc}

##### Abstract
Video prediction models based on convolutional net- works, recurrent networks, and their combinations often re- sult in blurry predictions. We identify an important con- tributing factor for imprecise predictions that has not been studied adequately in the literature: blind spots, i.e., lack of access to all relevant past information for accurately predicting the future. To address this issue, we introduce a fully context-aware architecture that captures the entire available past context for each pixel using Parallel Multi- Dimensional LSTM units and aggregates it using blending units. Our model outperforms a strong baseline network of 20 recurrent convolutional layers and yields state-of- the-art performance for next step prediction. Moreover, it does so with fewer parameters than several recently pro- posed models, and does not rely on deep convolutional net- works, multi-scale architectures, separation of background and foreground modeling, motion flow learning, or adver- sarial training. These results highlight that full awareness of past context is of crucial importance for video prediction.

##### Abstract (translated by Google)
基于卷积网络，循环网络及其组合的视频预测模型通常会导致模糊的预测。我们确定了一个重要的不确定预测因素，这些因素在文献中尚未得到充分研究：盲点，即缺乏准确预测未来的所有相关过去信息。为了解决这个问题，我们引入了完全上下文感知架构，该架构使用并行多维LSTM单元捕获每个像素的全部可用过去上下文，并使用混合单元对其进行聚合。我们的模型胜过了20个经常卷积层的强大基线网络，并为下一步预测提供了最先进的性能。此外，它使用的参数少于最近推荐的模型，并且不依赖于深度卷积网络，多尺度架构，背景和前景建模的分离，运动流学习或广告培训。这些结果强调，对视频预测至关重要的是对过去情境的全面了解。

##### URL
[http://arxiv.org/abs/1710.08518](http://arxiv.org/abs/1710.08518)

##### PDF
[http://arxiv.org/pdf/1710.08518](http://arxiv.org/pdf/1710.08518)

