---
layout: post
title: "Transductive Label Augmentation for Improved Deep Network Learning"
date: 2018-05-26 21:59:09
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification Deep_Learning
author: Ismail Elezi, Alessandro Torcinovich, Sebastiano Vascon, Marcello Pelillo
mathjax: true
---

* content
{:toc}

##### Abstract
A major impediment to the application of deep learning to real-world problems is the scarcity of labeled data. Small training sets are in fact of no use to deep networks as, due to the large number of trainable parameters, they will very likely be subject to overfitting phenomena. On the other hand, the increment of the training set size through further manual or semi-automatic labellings can be costly, if not possible at times. Thus, the standard techniques to address this issue are transfer learning and data augmentation, which consists of applying some sort of "transformation" to existing labeled instances to let the training set grow in size. Although this approach works well in applications such as image classification, where it is relatively simple to design suitable transformation operators, it is not obvious how to apply it in more structured scenarios. Motivated by the observation that in virtually all application domains it is easy to obtain unlabeled data, in this paper we take a different perspective and propose a \emph{label augmentation} approach. We start from a small, curated labeled dataset and let the labels propagate through a larger set of unlabeled data using graph transduction techniques. This allows us to naturally use (second-order) similarity information which resides in the data, a source of information which is typically neglected by standard augmentation techniques. In particular, we show that by using known game theoretic transductive processes we can create larger and accurate enough labeled datasets which use results in better trained neural networks. Preliminary experiments are reported which demonstrate a consistent improvement over standard image classification datasets.

##### Abstract (translated by Google)
将深度学习应用于现实世界问题的主要障碍是标记数据的稀缺性。小型训练集对于深度网络实际上是没有用的，因为由于大量的可训练参数，它们很可能会出现过度拟合现象。另一方面，通过进一步的手动或半自动化标记增加训练集大小可能是昂贵的，如果不可能的话。因此，解决这个问题的标准技术是转移学习和数据增强，其中包括对现有的标记实例应用某种“转换”以使训练集的规模增大。尽管这种方法在诸如图像分类等应用程序中运行良好，但设计合适的转换操作符相对简单，但如何将其应用于更多结构化的情况并不明显。受到观察的启发，在几乎所有的应用领域中，很容易获得未标记的数据，本文中我们采取不同的观点并提出了一种\ emph {标签增强}方法。我们从一个小型的有标签的数据集开始，并使用图形转换技术让标签通过一组更大的未标记数据进行传播。这允许我们自然地使用驻留在数据中的（二阶）相似性信息，这是通常由标准增强技术忽略的信息源。特别是，我们表明通过使用已知的博弈理论转导过程，我们可以创建更大，更准确的标记数据集，这些数据集使用更好的训练神经网络中的结果。报告初步实验显示了对标准图像分类数据集的一致改进。

##### URL
[http://arxiv.org/abs/1805.10546](http://arxiv.org/abs/1805.10546)

##### PDF
[http://arxiv.org/pdf/1805.10546](http://arxiv.org/pdf/1805.10546)

