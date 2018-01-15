---
layout: post
title: "Real-world Anomaly Detection in Surveillance Videos"
date: 2018-01-12 18:46:23
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection Recognition
author: Waqas Sultani, Chen Chen, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Surveillance videos are able to capture a variety of realistic anomalies. In this paper, we propose to learn anomalies by exploiting both normal and anomalous videos. To avoid annotating the anomalous segments or clips in training videos, which is very time consuming, we propose to learn anomaly through the deep multiple instance ranking framework by leveraging weakly labeled training videos, i.e. the training labels (anomalous or normal) are at video-level instead of clip-level. In our approach, we consider normal and anomalous videos as bags and video segments as instances in multiple instance learning (MIL), and automatically learn a deep anomaly ranking model that predicts high anomaly scores for anomalous video segments. Furthermore, we introduce sparsity and temporal smoothness constraints in the ranking loss function to better localize anomaly during training. We also introduce a new large-scale first of its kind dataset of 128 hours of videos. It consists of 1900 long and untrimmed real-world surveillance videos, with 13 realistic anomalies such as fighting, road accident, burglary, robbery, etc. as well as normal activities. This dataset can be used for two tasks. First, general anomaly detection considering all anomalies in one group and all normal activities in another group. Second, for recognizing each of 13 anomalous activities. Our experimental results show that our MIL method for anomaly detection achieves significant improvement on anomaly detection performance as compared to the state-of-the-art approaches. We provide the results of several recent deep learning baselines on anomalous activity recognition. The low recognition performance of these baselines reveals that our dataset is very challenging and opens more opportunities for future work.

##### Abstract (translated by Google)
监视视频能够捕捉各种现实的异常情况。在本文中，我们建议通过利用正常视频和异常视频来学习异常情况。为了避免在训练视频中注释异常片段或片段，这是非常耗时的，我们建议通过利用弱标签的训练视频通过深度多实例排名框架来学习异常，即训练标签（异常或正常）级别而不是剪辑级别。在我们的方法中，我们将常规视频和异常视频视为多个实例学习（MIL）中的实例，并自动学习一个预测异常视频片段的高异常分数的深度异常排名模型。此外，我们引入排序损失函数中的稀疏性和时间平滑性约束来更好地定位训练期间的异常。我们还引入了一个全新的大规模的128小时视频数据集。它由1900个长期和未修剪的现实世界的监控视频组成，包括战斗，道路交通事故，爆窃，抢劫等13个现实异常以及正常活动。这个数据集可以用于两个任务。首先，考虑一个组中的所有异常和另一个组中的所有正常活动的一般异常检测。其次，对13个异常活动中的每一个进行认识。我们的实验结果表明，与最先进的方法相比，我们的用于异常检测的MIL方法在异常检测性能方面实现了显着的改进。我们提供了近期有关异常活动识别的深度学习基线的结果。这些基线的低识别性能表明，我们的数据集非常具有挑战性，为未来的工作开辟了更多的机会。

##### URL
[http://arxiv.org/abs/1801.04264](http://arxiv.org/abs/1801.04264)

##### PDF
[http://arxiv.org/pdf/1801.04264](http://arxiv.org/pdf/1801.04264)

