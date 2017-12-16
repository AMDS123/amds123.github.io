---
layout: post
title: "Weakly Supervised Action Learning with RNN based Fine-to-coarse Modeling"
date: 2017-10-09 10:10:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Inference RNN
author: Alexander Richard, Hilde Kuehne, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for weakly supervised learning of human actions. Given a set of videos and an ordered list of the occurring actions, the goal is to infer start and end frames of the related action classes within the video and to train the respective action classifiers without any need for hand labeled frame boundaries. To address this task, we propose a combination of a discriminative representation of subactions, modeled by a recurrent neural network, and a coarse probabilistic model to allow for a temporal alignment and inference over long sequences. While this system alone already generates good results, we show that the performance can be further improved by approximating the number of subactions to the characteristics of the different action classes. To this end, we adapt the number of subaction classes by iterating realignment and reestimation during training. The proposed system is evaluated on two benchmark datasets, the Breakfast and the Hollywood extended dataset, showing a competitive performance on various weak learning tasks such as temporal action segmentation and action alignment.

##### Abstract (translated by Google)
我们提出一种弱监督学习人类行为的方法。给定一组视频和发生的动作的有序列表，目标是推断视频内相关动作类别的开始和结束帧，并且训练相应的动作分类器，而不需要手动标记的帧边界。为了解决这个任务，我们提出了一个由循环神经网络模型化的子动作的区分表示和一个粗概率模型的组合，以允许在长序列上的时间对齐和推理。虽然这个系统本身已经产生了良好的结果，但是我们表明，通过将子动作的数量近似于不同动作类别的特征，可以进一步提高性能。为此，我们通过迭代训练期间的重新对齐和重新估计来调整子事务类的数量。所提出的系统在两个基准数据集（早餐和好莱坞扩展数据集）上进行评估，显示了对诸如时间动作分割和动作对齐等各种弱学习任务的竞争性表现。

##### URL
[https://arxiv.org/abs/1703.08132](https://arxiv.org/abs/1703.08132)

##### PDF
[https://arxiv.org/pdf/1703.08132](https://arxiv.org/pdf/1703.08132)

