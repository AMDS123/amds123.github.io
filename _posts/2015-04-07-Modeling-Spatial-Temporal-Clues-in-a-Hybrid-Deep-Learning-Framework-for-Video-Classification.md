---
layout: post
title: "Modeling Spatial-Temporal Clues in a Hybrid Deep Learning Framework for Video Classification"
date: 2015-04-07 11:53:46
categories: arXiv_CV
tags: arXiv_CV CNN Video_Classification RNN Classification Deep_Learning Relation
author: Zuxuan Wu, Xi Wang, Yu-Gang Jiang, Hao Ye, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
Classifying videos according to content semantics is an important problem with a wide range of applications. In this paper, we propose a hybrid deep learning framework for video classification, which is able to model static spatial information, short-term motion, as well as long-term temporal clues in the videos. Specifically, the spatial and the short-term motion features are extracted separately by two Convolutional Neural Networks (CNN). These two types of CNN-based features are then combined in a regularized feature fusion network for classification, which is able to learn and utilize feature relationships for improved performance. In addition, Long Short Term Memory (LSTM) networks are applied on top of the two features to further model longer-term temporal clues. The main contribution of this work is the hybrid learning framework that can model several important aspects of the video data. We also show that (1) combining the spatial and the short-term motion features in the regularized fusion network is better than direct classification and fusion using the CNN with a softmax layer, and (2) the sequence-based LSTM is highly complementary to the traditional classification strategy without considering the temporal frame orders. Extensive experiments are conducted on two popular and challenging benchmarks, the UCF-101 Human Actions and the Columbia Consumer Videos (CCV). On both benchmarks, our framework achieves to-date the best reported performance: $91.3\%$ on the UCF-101 and $83.5\%$ on the CCV.

##### Abstract (translated by Google)
根据内容语义对视频进行分类是广泛应用的重要问题。在本文中，我们提出了一个混合的视频分类深度学习框架，它能够对视频中的静态空间信息，短时间运动以及长时间的线索进行建模。具体而言，空间和短期运动特征分别由两个卷积神经网络（CNN）提取。然后将这两种基于CNN的特征组合在正则化的特征融合网络中进行分类，从而能够学习和利用特征关系来提高性能。此外，长期短期记忆（LSTM）网络应用于这两个特征之上，以进一步模拟长期的时间线索。这项工作的主要贡献是混合学习框架，可以模拟视频数据的几个重要方面。 （1）正则化融合网络中的空间和短期运动特征相结合优于使用CNN和softmax层进行直接分类和融合，（2）基于序列的LSTM与传统的分类策略不考虑时间帧顺序。 UCF-101人类行动和哥伦比亚消费者视频（CCV）两个流行和具有挑战性的基准进行了广泛的实验。在这两个基准测试中，我们的框架实现了最新的报告性能：UCF-101上的$ 91.3 \％$和CCV上的$ 83.5 \％$。

##### URL
[https://arxiv.org/abs/1504.01561](https://arxiv.org/abs/1504.01561)

##### PDF
[https://arxiv.org/pdf/1504.01561](https://arxiv.org/pdf/1504.01561)

