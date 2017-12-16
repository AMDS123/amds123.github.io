---
layout: post
title: "Leveraging the Path Signature for Skeleton-based Human Action Recognition"
date: 2017-07-13 07:02:37
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Deep_Learning Recognition
author: Weixin Yang, Terry Lyons, Hao Ni, Cordelia Schmid, Lianwen Jin, Jiawei Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Human action recognition in videos is one of the most challenging tasks in computer vision. One important issue is how to design discriminative features for representing spatial context and temporal dynamics. Here, we introduce a path signature feature to encode information from intra-frame and inter-frame contexts. A key step towards leveraging this feature is to construct the proper trajectories (paths) for the data steam. In each frame, the correlated constraints of human joints are treated as small paths, then the spatial path signature features are extracted from them. In video data, the evolution of these spatial features over time can also be regarded as paths from which the temporal path signature features are extracted. Eventually, all these features are concatenated to constitute the input vector of a fully connected neural network for action classification. Experimental results on four standard benchmark action datasets, J-HMDB, SBU Dataset, Berkeley MHAD, and NTURGB+D demonstrate that the proposed approach achieves state-of-the-art accuracy even in comparison with recent deep learning based models.

##### Abstract (translated by Google)
视频中的人类行为识别是计算机视觉中最具挑战性的任务之一。一个重要的问题是如何设计用于表示空间上下文和时间动态的判别特征。在这里，我们引入一个路径签名特征来对来自帧内和帧间上下文的信息进行编码。利用这一功能的一个关键步骤是为数据流构建适当的轨迹（路径）。在每一帧中，将人体关节的相关约束作为小路径处理，然后从中提取空间路径签名特征。在视频数据中，随着时间的推移，这些空间特征的演变也可被视为提取时间路径特征特征的路径。最后，将所有这些特征连接起来构成一个完全连接的神经网络的输入向量，以进行行为分类。 J-HMDB，SBU数据集，Berkeley MHAD和NTURGB + D四个标准基准动作数据集的实验结果表明，即使与最近的基于深度学习的模型相比，所提出的方法也达到了最新的精确度。

##### URL
[https://arxiv.org/abs/1707.03993](https://arxiv.org/abs/1707.03993)

##### PDF
[https://arxiv.org/pdf/1707.03993](https://arxiv.org/pdf/1707.03993)

