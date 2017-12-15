---
layout: post
title: "Learning Latent Sub-events in Activity Videos Using Temporal Attention Filters"
date: 2016-12-26 11:16:33
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Memory_Networks Recognition
author: AJ Piergiovanni, Chenyou Fan, Michael S. Ryoo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we newly introduce the concept of temporal attention filters, and describe how they can be used for human activity recognition from videos. Many high-level activities are often composed of multiple temporal parts (e.g., sub-events) with different duration/speed, and our objective is to make the model explicitly learn such temporal structure using multiple attention filters and benefit from them. Our temporal filters are designed to be fully differentiable, allowing end-of-end training of the temporal filters together with the underlying frame-based or segment-based convolutional neural network architectures. This paper presents an approach of learning a set of optimal static temporal attention filters to be shared across different videos, and extends this approach to dynamically adjust attention filters per testing video using recurrent long short-term memory networks (LSTMs). This allows our temporal attention filters to learn latent sub-events specific to each activity. We experimentally confirm that the proposed concept of temporal attention filters benefits the activity recognition, and we visualize the learned latent sub-events.

##### Abstract (translated by Google)
在本文中，我们新引入时间关注过滤器的概念，并描述如何将它们用于视频的人类活动识别。许多高层次的活动往往由多个不同的时间段（例如，子事件）组成，我们的目标是使模型使用多重注意过滤器明确地学习这种时间结构，并从中受益。我们的时间滤波器被设计为完全可微分的，允许时间滤波器的端对端训练以及基础的基于帧的或基于分段的卷积神经网络架构。本文提出了一种学习一组最佳的静态时间关注过滤器以在不同的视频之间共享的方法，并且扩展了这种方法以使用经常性的长期短期记忆网络（LSTM）来动态调整每个测试视频的关注过滤器。这使我们的时间关注过滤器学习每个活动特有的潜在子事件。我们通过实验证实，所提出的时间关注过滤器的概念有利于活动的识别，并且我们将所学的潜在的子事件可视化。

##### URL
[https://arxiv.org/abs/1605.08140](https://arxiv.org/abs/1605.08140)

##### PDF
[https://arxiv.org/pdf/1605.08140](https://arxiv.org/pdf/1605.08140)

