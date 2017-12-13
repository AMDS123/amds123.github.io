---
layout: post
title: "Direction-aware Spatial Context Features for Shadow Detection"
date: 2017-12-12 06:29:51
categories: arXiv_CV
tags: arXiv_CV Attention RNN Detection
author: Xiaowei Hu, Lei Zhu, Chi-Wing Fu, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Shadow detection is a fundamental and challenging task, since it requires an understanding of global image semantics and there are various backgrounds around shadows. This paper presents a novel network for shadow detection by analyzing image context in a direction-aware manner. To achieve this, we first formulate the direction-aware attention mechanism in a spatial recurrent neural network (RNN) by introducing attention weights when aggregating spatial context features in the RNN. By learning these weights through training, we can recover direction-aware spatial context (DSC) for detecting shadows. This design is developed into the DSC module and embedded in a CNN to learn DSC features at different levels. Moreover, a weighted cross entropy loss is designed to make the training more effective. We employ two common shadow detection benchmark datasets and perform various experiments to evaluate our network. Experimental results show that our network outperforms state-of-the-art methods and achieves 97% accuracy and 38% reduction on balance error rate.

##### Abstract (translated by Google)
阴影检测是一项基本的和具有挑战性的任务，因为它需要对全局图像语义的理解，阴影周围有各种各样的背景。本文提出了一种新的网络阴影检测通过分析图像上下文的方向感知的方式。为了实现这个目标，我们首先在聚合RNN中的空间上下文特征时，引入注意力权重，在空间递归神经网络（RNN）中建立方向感知注意机制。通过训练学习这些权重，我们可以恢复方向感知空间上下文（DSC）来检测阴影。这个设计被开发成DSC模块并嵌入在CNN中以学习不同级别的DSC功能。此外，还设计了加权交叉熵损失，使训练更加有效。我们使用两个常见的阴影检测基准数据集，并执行各种实验来评估我们的网络。实验结果表明，我们的网络胜过最先进的方法，达到97％的准确率和38％的平衡错误率下降。

##### URL
[http://arxiv.org/abs/1712.04142](http://arxiv.org/abs/1712.04142)

##### PDF
[http://arxiv.org/pdf/1712.04142](http://arxiv.org/pdf/1712.04142)

