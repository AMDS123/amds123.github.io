---
layout: post
title: "Slow and steady feature analysis: higher order temporal coherence in video"
date: 2016-04-14 18:37:33
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Dinesh Jayaraman, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
How can unlabeled video augment visual learning? Existing methods perform "slow" feature analysis, encouraging the representations of temporally close frames to exhibit only small differences. While this standard approach captures the fact that high-level visual signals change slowly over time, it fails to capture *how* the visual content changes. We propose to generalize slow feature analysis to "steady" feature analysis. The key idea is to impose a prior that higher order derivatives in the learned feature space must be small. To this end, we train a convolutional neural network with a regularizer on tuples of sequential frames from unlabeled video. It encourages feature changes over time to be smooth, i.e., similar to the most recent changes. Using five diverse datasets, including unlabeled YouTube and KITTI videos, we demonstrate our method's impact on object, scene, and action recognition tasks. We further show that our features learned from unlabeled video can even surpass a standard heavily supervised pretraining approach.

##### Abstract (translated by Google)
未标记的视频如何增强视觉学习？现有的方法执行“慢”特征分析，鼓励时间上接近的帧的表示仅显示小的差异。虽然这种标准方法捕捉到高级视觉信号随着时间缓慢变化的事实，但它不能捕捉视觉内容如何变化。我们建议将慢特征分析推广到“稳定”特征分析。关键的想法是在学习的特征空间中的高阶导数必须小一些。为此，我们使用正规化器对来自无标签视频的连续帧元组进行卷积神经网络训练。它鼓励随着时间推移的特征变化是平滑的，即类似于最近的变化。使用五个不同的数据集，包括未标记的YouTube和KITTI视频，我们演示了我们的方法对对象，场景和动作识别任务的影响。我们进一步表明，我们从无标签视频中学到的特征甚至可以超过标准严格监督的预训练方法。

##### URL
[https://arxiv.org/abs/1506.04714](https://arxiv.org/abs/1506.04714)

##### PDF
[https://arxiv.org/pdf/1506.04714](https://arxiv.org/pdf/1506.04714)

