---
layout: post
title: "An unsupervised long short-term memory neural network for event detection in cell videos"
date: 2017-09-07 05:58:23
categories: arXiv_CV
tags: arXiv_CV Sparse CNN RNN Classification Detection
author: Ha Tran Hong Phan, Ashnil Kumar, David Feng, Michael Fulham, Jinman Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an automatic unsupervised cell event detection and classification method, which expands convolutional Long Short-Term Memory (LSTM) neural networks, for cellular events in cell video sequences. Cells in images that are captured from various biomedical applications usually have different shapes and motility, which pose difficulties for the automated event detection in cell videos. Current methods to detect cellular events are based on supervised machine learning and rely on tedious manual annotation from investigators with specific expertise. So that our LSTM network could be trained in an unsupervised manner, we designed it with a branched structure where one branch learns the frequent, regular appearance and movements of objects and the second learns the stochastic events, which occur rarely and without warning in a cell video sequence. We tested our network on a publicly available dataset of densely packed stem cell phase-contrast microscopy images undergoing cell division. This dataset is considered to be more challenging that a dataset with sparse cells. We compared our method to several published supervised methods evaluated on the same dataset and to a supervised LSTM method with a similar design and configuration to our unsupervised method. We used an F1-score, which is a balanced measure for both precision and recall. Our results show that our unsupervised method has a higher or similar F1-score when compared to two fully supervised methods that are based on Hidden Conditional Random Fields (HCRF), and has comparable accuracy with the current best supervised HCRF-based method. Our method was generalizable as after being trained on one video it could be applied to videos where the cells were in different conditions. The accuracy of our unsupervised method approached that of its supervised counterpart.

##### Abstract (translated by Google)
我们提出了一种自动无监督的细胞事件检测和分类方法，它扩展了卷积式长时间短期记忆（LSTM）神经网络，用于细胞视频序列中的细胞事件。从各种生物医学应用中捕获的图像中的细胞通常具有不同的形状和运动性，这为细胞视频中的自动事件检测造成困难。目前用于检测细胞事件的方法基于监督机器学习，并且依赖具有特定专业知识的调查人员的乏味的手动注释。为了使我们的LSTM网络能够以无监督的方式进行训练，我们设计了一个分支结构，一个分支学习频繁，规律的物体的出现和运动，第二个学习随机事件，这些事件在一个小区中很少发生，没有警告视频序列。我们在密集包装的干细胞相差显微图像进行细胞分裂的公开数据集上测试了我们的网络。这个数据集被认为是具有稀疏单元格的数据集更具挑战性。我们将我们的方法与在同一数据集上评估的几个已发布的监督方法进行了比较，并将其与我们的无监督方法进行了类似设计和配置的监督LSTM方法进行了比较。我们使用了F1分数，这是精确度和召回率的平衡度量。我们的结果表明，与基于隐式条件随机场（HCRF）的两个完全监督方法相比，我们的无监督方法具有更高或相似的F1分数，并且具有与当前最佳监督HCRF方法相当的准确性。我们的方法是可以普遍化的，因为在一个视频上被训练之后，它可以被应用到细胞在不同条件下的视频。我们的无监督方法的准确性接近其监督对手的准确性。

##### URL
[https://arxiv.org/abs/1709.02081](https://arxiv.org/abs/1709.02081)

##### PDF
[https://arxiv.org/pdf/1709.02081](https://arxiv.org/pdf/1709.02081)

