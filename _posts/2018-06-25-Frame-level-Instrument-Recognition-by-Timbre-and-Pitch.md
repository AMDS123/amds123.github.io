---
layout: post
title: "Frame-level Instrument Recognition by Timbre and Pitch"
date: 2018-06-25 17:33:04
categories: arXiv_SD
tags: arXiv_SD Salient CNN Classification Prediction Recognition
author: Yun-Ning Hung, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Instrument recognition is a fundamental task in music information retrieval, yet little has been done to predict the presence of instruments in multi-instrument music for each time frame. This task is important for not only automatic transcription but also many retrieval problems. In this paper, we use the newly released MusicNet dataset to study this front, by building and evaluating a convolutional neural network for making frame-level instrument prediction. We consider it as a multi-label classification problem for each frame and use frame-level annotations as the supervisory signal in training the network. Moreover, we experiment with different ways to incorporate pitch information to our model, with the premise that doing so informs the model the notes that are active per frame, and also encourages the model to learn relative rates of energy buildup in the harmonic partials of different instruments. Experiments show salient performance improvement over baseline methods. We also report an analysis probing how pitch information helps the instrument prediction task. Code and experiment details can be found at \url{https://biboamy.github.io/instrument-recognition/}.

##### Abstract (translated by Google)
乐器识别是音乐信息检索的基本任务，但对于每个时间帧预测多乐器音乐中乐器的存在的工作很少。这项任务不仅对自动转录而且对许多检索问题都很重要。在本文中，我们使用新发布的MusicNet数据集来研究这个前沿，通过构建和评估用于进行帧级仪器预测的卷积神经网络。我们将其视为每个帧的多标签分类问题，并将帧级别标注用作训练网络的监督信号。此外，我们尝试用不同的方式将音高信息合并到我们的模型中，前提是这样做会将每帧活动的音符通知给模型，并且还鼓励模型学习不同谐波分量中能量累积的相对速率仪器。实验显示比基线方法显着的性能提升。我们还报告了一项分析，探讨音高信息如何帮助仪器预测任务。代码和实验细节可以在\ url {https://biboamy.github.io/instrument-recognition/}找到。

##### URL
[http://arxiv.org/abs/1806.09587](http://arxiv.org/abs/1806.09587)

##### PDF
[http://arxiv.org/pdf/1806.09587](http://arxiv.org/pdf/1806.09587)

