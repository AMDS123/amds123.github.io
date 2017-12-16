---
layout: post
title: "Efficient Dense Labeling of Human Activity Sequences from Wearables using Fully Convolutional Networks"
date: 2017-02-20 23:44:54
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Rui Yao, Guosheng Lin, Qinfeng Shi, Damith Ranasinghe
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing human activities in a sequence is a challenging area of research in ubiquitous computing. Most approaches use a fixed size sliding window over consecutive samples to extract features---either handcrafted or learned features---and predict a single label for all samples in the window. Two key problems emanate from this approach: i) the samples in one window may not always share the same label. Consequently, using one label for all samples within a window inevitably lead to loss of information; ii) the testing phase is constrained by the window size selected during training while the best window size is difficult to tune in practice. We propose an efficient algorithm that can predict the label of each sample, which we call dense labeling, in a sequence of human activities of arbitrary length using a fully convolutional network. In particular, our approach overcomes the problems posed by the sliding window step. Additionally, our algorithm learns both the features and classifier automatically. We release a new daily activity dataset based on a wearable sensor with hospitalized patients. We conduct extensive experiments and demonstrate that our proposed approach is able to outperform the state-of-the-arts in terms of classification and label misalignment measures on three challenging datasets: Opportunity, Hand Gesture, and our new dataset.

##### Abstract (translated by Google)
在一个序列中识别人类活动是无所不在的计算领域的一个具有挑战性的研究领域。大多数方法在连续样本上使用固定大小的滑动窗口来提取特征 - 手工或学习特征 - 并预测窗口中所有样本的单个标签。这种方法产生了两个关键问题：i）一个窗口中的样本可能不总是共享相同的标签。因此，对一个窗口内的所有样本使用一个标签不可避免地会导致信息的丢失; ii）测试阶段受到在训练期间选择的窗口大小的限制，而最佳窗口大小在实践中难以调整。我们提出了一个有效的算法，可以使用完全卷积网络在任意长度的人类活动序列中预测每个样本的标签，我们称之为稠密标签。特别是，我们的方法克服了滑动窗口步骤带来的问题。此外，我们的算法自动学习功能和分类器。我们发布了一个新的日常活动数据集基于可穿戴式传感器与住院患者。我们进行了广泛的实验，并证明我们提出的方法能够在三个具有挑战性的数据集（机会，手势和我们的新数据集）上的分类和标签错位测量方面超越现有技术水平。

##### URL
[https://arxiv.org/abs/1702.06212](https://arxiv.org/abs/1702.06212)

##### PDF
[https://arxiv.org/pdf/1702.06212](https://arxiv.org/pdf/1702.06212)

