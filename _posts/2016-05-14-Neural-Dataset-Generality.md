---
layout: post
title: "Neural Dataset Generality"
date: 2016-05-14 03:17:15
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Recognition
author: Ragav Venkatesan, Vijetha Gattupalli, Baoxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Often the filters learned by Convolutional Neural Networks (CNNs) from different datasets appear similar. This is prominent in the first few layers. This similarity of filters is being exploited for the purposes of transfer learning and some studies have been made to analyse such transferability of features. This is also being used as an initialization technique for different tasks in the same dataset or for the same task in similar datasets. Off-the-shelf CNN features have capitalized on this idea to promote their networks as best transferable and most general and are used in a cavalier manner in day-to-day computer vision tasks. It is curious that while the filters learned by these CNNs are related to the atomic structures of the images from which they are learnt, all datasets learn similar looking low-level filters. With the understanding that a dataset that contains many such atomic structures learn general filters and are therefore useful to initialize other networks with, we propose a way to analyse and quantify generality among datasets from their accuracies on transferred filters. We applied this metric on several popular character recognition, natural image and a medical image dataset, and arrived at some interesting conclusions. On further experimentation we also discovered that particular classes in a dataset themselves are more general than others.

##### Abstract (translated by Google)
通常来自不同数据集的卷积神经网络（CNN）学习的滤波器看起来相似。这在前几个层次中是突出的。过滤器的这种相似性正在被用于转移学习的目的，并且已经进行了一些研究来分析这些特征的可转移性。这也被用作相同数据集中的不同任务的初始化技术，或用于相似数据集中的相同任务。现成的CNN特性利用了这个想法来促进他们的网络作为最好的可转换和最普通的网络，并且在日常的计算机视觉任务中以一种傲慢的方式被使用。奇怪的是，虽然这些CNN学习的滤波器与它们学习的图像的原子结构有关，但是所有的数据集都学习了类似的低级滤波器。由于认识到包含许多这样的原子结构的数据集学习通用滤波器并因此有助于初始化其他网络，所以我们提出了一种根据其在传输的滤波器上的精度来分析和量化数据集之间的一般性的方法。我们将这个度量应用于几种流行的字符识别，自然图像和医学图像数据集，并得出了一些有趣的结论。在进一步的实验中，我们也发现数据集中的特定类比其他类更普遍。

##### URL
[https://arxiv.org/abs/1605.04369](https://arxiv.org/abs/1605.04369)

##### PDF
[https://arxiv.org/pdf/1605.04369](https://arxiv.org/pdf/1605.04369)

