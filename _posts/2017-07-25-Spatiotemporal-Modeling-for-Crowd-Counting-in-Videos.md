---
layout: post
title: "Spatiotemporal Modeling for Crowd Counting in Videos"
date: 2017-07-25 10:02:33
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning RNN Deep_Learning Relation
author: Feng Xiong, Xingjian Shi, Dit-Yan Yeung
mathjax: true
---

* content
{:toc}

##### Abstract
Region of Interest (ROI) crowd counting can be formulated as a regression problem of learning a mapping from an image or a video frame to a crowd density map. Recently, convolutional neural network (CNN) models have achieved promising results for crowd counting. However, even when dealing with video data, CNN-based methods still consider each video frame independently, ignoring the strong temporal correlation between neighboring frames. To exploit the otherwise very useful temporal information in video sequences, we propose a variant of a recent deep learning model called convolutional LSTM (ConvLSTM) for crowd counting. Unlike the previous CNN-based methods, our method fully captures both spatial and temporal dependencies. Furthermore, we extend the ConvLSTM model to a bidirectional ConvLSTM model which can access long-range information in both directions. Extensive experiments using four publicly available datasets demonstrate the reliability of our approach and the effectiveness of incorporating temporal information to boost the accuracy of crowd counting. In addition, we also conduct some transfer learning experiments to show that once our model is trained on one dataset, its learning experience can be transferred easily to a new dataset which consists of only very few video frames for model adaptation.

##### Abstract (translated by Google)
感兴趣区（ROI）人群计数可以被表述为学习从图像或视频帧到人群密度图的映射的回归问题。最近，卷积神经网络（CNN）模型已经取得了令人鼓舞的成果。然而，即使在处理视频数据时，基于CNN的方法仍然独立地考虑每个视频帧，忽略了相邻帧之间的强时间相关性。为了利用视频序列中另外非常有用的时间信息，我们提出了一种最近的用于人群计数的称为卷积LSTM（ConvLSTM）的深度学习模型的变体。与以前的基于CNN的方法不同，我们的方法完全捕获空间和时间依赖性。此外，我们将ConvLSTM模型扩展为双向ConvLSTM模型，可以在两个方向上访问远程信息。使用四个公开可用的数据集的大量实验证明了我们的方法的可靠性以及合并时间信息以提高人群计数准确性的有效性。此外，我们还进行了一些转移学习实验，表明一旦我们的模型在一个数据集上进行训练，其学习经验可以很容易地转移到一个新的数据集，其中只有很少的视频帧用于模型适应。

##### URL
[https://arxiv.org/abs/1707.07890](https://arxiv.org/abs/1707.07890)

##### PDF
[https://arxiv.org/pdf/1707.07890](https://arxiv.org/pdf/1707.07890)

