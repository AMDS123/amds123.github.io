---
layout: post
title: "Combining Heterogeneously Labeled Datasets For Training Segmentation Networks"
date: 2018-07-24 07:43:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN
author: Jana Kemnitz, Christian F. Baumgartner, Wolfgang Wirth, Felix Eckstein, Sebastian K. Eder, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of medical images is an important step towards analyzing and tracking disease related morphological alterations in the anatomy. Convolutional neural networks (CNNs) have recently emerged as a powerful tool for many segmentation tasks in medical imaging. The performance of CNNs strongly depends on the size of the training data and combining data from different sources is an effective strategy for obtaining larger training datasets. However, this is often challenged by heterogeneous labeling of the datasets. For instance, one of the dataset may be missing labels or a number of labels may have been combined into a super label. In this work we propose a cost function which allows integration of multiple datasets with heterogeneous label subsets into a joint training. We evaluated the performance of this strategy on thigh MR and a cardiac MR datasets in which we artificially merged labels for half of the data. We found the proposed cost function substantially outperforms a naive masking approach, obtaining results very close to using the full annotations.

##### Abstract (translated by Google)
准确分割医学图像是分析和跟踪解剖学中与疾病相关的形态学改变的重要步骤。卷积神经网络（CNN）最近已成为医学成像中许多分割任务的强大工具。 CNN的性能很大程度上取决于训练数据的大小，并且组合来自不同来源的数据是获得更大训练数据集的有效策略。然而，这经常受到数据集的异构标记的挑战。例如，其中一个数据集可能缺少标签，或者许多标签可能已组合成超级标签。在这项工作中，我们提出了一个成本函数，它允许将多个数据集与异构标签子集集成到一个联合培训中。我们评估了该策略在大腿MR和心脏MR数据集上的性能，其中我们人工合并了一半数据的标签。我们发现建议的成本函数基本上优于天真的掩蔽方法，获得的结果非常接近于使用完整的注释。

##### URL
[https://arxiv.org/abs/1807.08935](https://arxiv.org/abs/1807.08935)

##### PDF
[https://arxiv.org/pdf/1807.08935](https://arxiv.org/pdf/1807.08935)

