---
layout: post
title: "A Twofold Siamese Network for Real-Time Object Tracking"
date: 2018-02-24 07:57:52
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Image_Classification Object_Tracking Classification
author: Anfeng He, Chong Luo, Xinmei Tian, Wenjun Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Observing that Semantic features learned in an image classification task and Appearance features learned in a similarity matching task complement each other, we build a twofold Siamese network, named SA-Siam, for real-time object tracking. SA-Siam is composed of a semantic branch and an appearance branch. Each branch is a similarity-learning Siamese network. An important design choice in SA-Siam is to separately train the two branches to keep the heterogeneity of the two types of features. In addition, we propose a channel attention mechanism for the semantic branch. Channel-wise weights are computed according to the channel activations around the target position. While the inherited architecture from SiamFC \cite{SiamFC} allows our tracker to operate beyond real-time, the twofold design and the attention mechanism significantly improve the tracking performance. The proposed SA-Siam outperforms all other real-time trackers by a large margin on OTB-2013/50/100 benchmarks.

##### Abstract (translated by Google)
观察到在图像分类任务中学习到的语义特征和在相似匹配任务中学习到的外观特征相互补充，我们构建了一个名为SA-Siam的双重连接网络，用于实时对象跟踪。 SA-Siam由语义分支和外观分支组成。每个分支都是一个相似学习的连体网络。 SA-Siam的一个重要设计选择是分别训练两个分支以保持两种特征的异质性。另外，我们提出了语义分支的渠道关注机制。通道权重根据目标位置周围的通道激活进行计算。虽然SiamFC \ cite {SiamFC}的继承架构允许我们的追踪器实时运行，但双重设计和关注机制显着提高了追踪性能。在OTB-2013/50/100基准测试中，拟议的SA-Siam优于所有其他实时跟踪器。

##### URL
[http://arxiv.org/abs/1802.08817](http://arxiv.org/abs/1802.08817)

##### PDF
[http://arxiv.org/pdf/1802.08817](http://arxiv.org/pdf/1802.08817)

