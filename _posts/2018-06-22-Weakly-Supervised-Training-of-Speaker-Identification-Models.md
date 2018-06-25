---
layout: post
title: "Weakly Supervised Training of Speaker Identification Models"
date: 2018-06-22 12:15:35
categories: arXiv_CL
tags: arXiv_CL Weakly_Supervised
author: Martin Karu, Tanel Alum&#xe4;e
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach for training speaker identification models in a weakly supervised manner. We concentrate on the setting where the training data consists of a set of audio recordings and the speaker annotation is provided only at the recording level. The method uses speaker diarization to find unique speakers in each recording, and i-vectors to project the speech of each speaker to a fixed-dimensional vector. A neural network is then trained to map i-vectors to speakers, using a special objective function that allows to optimize the model using recording-level speaker labels. We report experiments on two different real-world datasets. On the VoxCeleb dataset, the method provides 94.6% accuracy on a closed set speaker identification task, surpassing the baseline performance by a large margin. On an Estonian broadcast news dataset, the method provides 66% time-weighted speaker identification recall at 93% precision.

##### Abstract (translated by Google)
我们提出了一种以弱监督方式训练说话人识别模型的方法。我们专注于训练数据由一组录音组成的设置，并且仅在录音级别提供说话者注释。该方法使用扬声器diarization在每个记录中查找唯一的说话者，以及将每个说话者的语音投影到固定维向量的i向量。然后训练神经网络，将i矢量映射到扬声器，使用特殊的目标函数，使用录音级扬声器标签优化模型。我们报告两个不同的真实世界数据集的实验。在VoxCeleb数据集上，该方法为闭合说话人识别任务提供了94.6％的准确度，大幅超越了基线表现。在爱沙尼亚广播新闻数据集中，该方法提供了66％的时间加权说话人识别调用，精确度为93％。

##### URL
[http://arxiv.org/abs/1806.08621](http://arxiv.org/abs/1806.08621)

##### PDF
[http://arxiv.org/pdf/1806.08621](http://arxiv.org/pdf/1806.08621)

