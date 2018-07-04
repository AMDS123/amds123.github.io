---
layout: post
title: "A Spatial and Temporal Features Mixture Model with Body Parts for Video-based Person Re-Identification"
date: 2018-07-03 04:33:22
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN RNN
author: Jie Liu, Cheng Sun, Xiang Xu, Baomin Xu, Shuangyuan Yu
mathjax: true
---

* content
{:toc}

##### Abstract
The video-based person re-identification is to recognize a person under different cameras, which is a crucial task applied in visual surveillance system. Most previous methods mainly focused on the feature of full body in the frame. In this paper we propose a novel Spatial and Temporal Features Mixture Model (STFMM) based on convolutional neural network (CNN) and recurrent neural network (RNN), in which the human body is split into $N$ parts in horizontal direction so that we can obtain more specific features. The proposed method skillfully integrates features of each part to achieve more expressive representation of each person. We first split the video sequence into $N$ part sequences which include the information of head, waist, legs and so on. Then the features are extracted by STFMM whose $2N$ inputs are obtained from the developed Siamese network, and these features are combined into a discriminative representation for one person. Experiments are conducted on the iLIDS-VID and PRID-2011 datasets. The results demonstrate that our approach outperforms existing methods for video-based person re-identification. It achieves a rank-1 CMC accuracy of 74\% on the iLIDS-VID dataset, exceeding the the most recently developed method ASTPN by 12\%. For the cross-data testing, our method achieves a rank-1 CMC accuracy of 48\% exceeding the ASTPN method by 18\%, which shows that our model has significant stability.

##### Abstract (translated by Google)
基于视频的人物重新识别是识别不同摄像机下的人，这是视觉监控系统中应用的关键任务。以前的大多数方法主要关注框架中全身的特征。在本文中，我们提出了一种基于卷积神经网络（CNN）和递归神经网络（RNN）的新型时空特征混合模型（STFMM），其中人体在水平方向上被分成$ N $个部分，这样我们就可以了可以获得更具体的功能。所提出的方法巧妙地集成了每个部分的特征，以实现每个人的更具表现力的表现。我们首先将视频序列分成$ N $部分序列，其中包括头部，腰部，腿部等信息。然后由STFMM提取特征，其中$ 2N $输入是从开发的Siamese网络获得的，并且这些特征被组合成一个人的辨别表示。实验在iLIDS-VID和PRID-2011数据集上进行。结果表明，我们的方法优于现有的基于视频的人员重新识别方法。它在iLIDS-VID数据集上达到了74％的1级CMC准确度，超过了最近开发的方法ASTPN 12％。对于跨数据测试，我们的方法实现了超过ASTPN方法的18％的1级CMC精度18％，这表明我们的模型具有显着的稳定性。

##### URL
[https://arxiv.org/abs/1807.00975](https://arxiv.org/abs/1807.00975)

##### PDF
[https://arxiv.org/pdf/1807.00975](https://arxiv.org/pdf/1807.00975)

