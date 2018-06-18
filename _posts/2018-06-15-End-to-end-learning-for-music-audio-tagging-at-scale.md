---
layout: post
title: "End-to-end learning for music audio tagging at scale"
date: 2018-06-15 08:04:37
categories: arXiv_SD
tags: arXiv_SD Knowledge CNN Deep_Learning
author: Jordi Pons, Oriol Nieto, Matthew Prockup, Erik Schmidt, Andreas Ehmann, Xavier Serra
mathjax: true
---

* content
{:toc}

##### Abstract
The lack of data tends to limit the outcomes of deep learning research, particularly when dealing with end-to-end learning stacks processing raw data such as waveforms. In this study, 1.2M tracks annotated with musical labels are available to train our end-to-end models. This large amount of data allows us to unrestrictedly explore two different design paradigms for music auto-tagging: assumption-free models - using waveforms as input with very small convolutional filters; and models that rely on domain knowledge - log-mel spectrograms with a convolutional neural network designed to learn timbral and temporal features. Our work focuses on studying how these two types of deep architectures perform when datasets of variable size are available for training: the MagnaTagATune (25k songs), the Million Song Dataset (240k songs), and a private dataset of 1.2M songs. Our experiments suggest that music domain assumptions are relevant when not enough training data are available, thus showing how waveform-based models outperform spectrogram-based ones in large-scale data scenarios.

##### Abstract (translated by Google)
缺乏数据往往会限制深度学习研究的成果，特别是在处理处理原始数据（如波形）的端到端学习堆栈时。在这项研究中，可以使用音乐标签注释的120万首曲目来训练我们的端到端模型。这种大量数据使我们能够无限制地探索两种不同的音乐自动标记设计范例：无假设模型 - 使用波形作为非常小的卷积滤波器的输入;以及依赖领域知识的模型 - 用卷积神经网络记录梅尔谱图以设计学习音色和时间特征。我们的工作重点研究当可变大小的数据集可用于训练时，这两种深层架构如何执行：MagnaTagATune（25k首歌曲），百万首歌曲数据集（240k首歌曲）以及一首1.2M歌曲的私有数据集。我们的实验表明，当没有足够的训练数据可用时，音乐领域假设是相关的，从而显示在大规模数据场景中基于波形的模型如何胜过基于频谱图的模型。

##### URL
[http://arxiv.org/abs/1711.02520](http://arxiv.org/abs/1711.02520)

##### PDF
[http://arxiv.org/pdf/1711.02520](http://arxiv.org/pdf/1711.02520)

