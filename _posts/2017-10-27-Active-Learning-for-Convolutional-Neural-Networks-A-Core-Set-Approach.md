---
layout: post
title: "Active Learning for Convolutional Neural Networks: A Core-Set Approach"
date: 2017-10-27 20:30:22
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Ozan Sener, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have been successfully applied to many recognition and learning tasks using a universal recipe; training a deep model on a very large dataset of supervised examples. However, this approach is rather restrictive in practice since collecting a large set of labeled images is very expensive. One way to ease this problem is coming up with smart ways for choosing images to be labelled from a very large collection (ie. active learning). Our empirical study suggests that many of the active learning heuristics in the literature are not effective when applied to CNNs in batch setting. Inspired by these limitations, we define the problem of active learning as core-set selection, ie. choosing set of points such that a model learned over the selected subset is competitive for the remaining data points. We further present a theoretical result characterizing the performance of any selected subset using the geometry of the datapoints. As an active learning algorithm, we choose the subset which is expected to yield best result according to our characterization. Our experiments show that the proposed method significantly outperforms existing approaches in image classification experiments by a large margin.

##### Abstract (translated by Google)
卷积神经网络（CNN）已成功应用于许多识别和学习任务使用通用配方;在监督例子的非常大的数据集上训练一个深层模型。然而，这种方法在实践中是相当严格的，因为收集大量标记的图像是非常昂贵的。解决这个问题的一个方法就是用一个非常大的集合（即主动学习）来选择图像进行标记的智能方法。我们的实证研究表明，文献中的许多主动学习启发式算法在批处理中应用于CNN时是无效的。受到这些限制的启发，我们将主动学习的问题定义为核心集合选择。选择一组点，使得在所选择的子集上学习的模型对于其余数据点是有竞争力的。我们进一步提出了一个理论结果，表征了使用数据点几何的任何选定子集的性能。作为主动学习算法，我们根据我们的表征选择期望产生最佳结果的子集。实验结果表明，该方法大大优于现有的图像分类实验方法。

##### URL
[https://arxiv.org/abs/1708.00489](https://arxiv.org/abs/1708.00489)

##### PDF
[https://arxiv.org/pdf/1708.00489](https://arxiv.org/pdf/1708.00489)

