---
layout: post
title: "Interpreting Convolutional Neural Networks Through Compression"
date: 2017-11-07 08:10:52
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Reza Abbasi-Asl, Bin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) achieve state-of-the-art performance in a wide variety of tasks in computer vision. However, interpreting CNNs still remains a challenge. This is mainly due to the large number of parameters in these networks. Here, we investigate the role of compression and particularly pruning filters in the interpretation of CNNs. We exploit our recently-proposed greedy structural compression scheme that prunes filters in a trained CNN. In our compression, the filter importance index is defined as the classification accuracy reduction (CAR) of the network after pruning that filter. The filters are then iteratively pruned based on the CAR index. We demonstrate the interpretability of CAR-compressed CNNs by showing that our algorithm prunes filters with visually redundant pattern selectivity. Specifically, we show the importance of shape-selective filters for object recognition, as opposed to color-selective filters. Out of top 20 CAR-pruned filters in AlexNet, 17 of them in the first layer and 14 of them in the second layer are color-selective filters. Finally, we introduce a variant of our CAR importance index that quantifies the importance of each image class to each CNN filter. We show that the most and the least important class labels present a meaningful interpretation of each filter that is consistent with the visualized pattern selectivity of that filter.

##### Abstract (translated by Google)
卷积神经网络（CNN）在计算机视觉的各种任务中实现了最先进的性能。但是，解释CNN仍然是一个挑战。这主要是由于这些网络中大量的参数。在这里，我们调查压缩的作用，特别是修剪过滤器在解释CNN中的作用。我们利用我们最近提出的贪婪结构压缩方案，在受过训练的CNN中修剪滤波器。在我们的压缩中，滤波器重要性指数被定义为在删除滤波器之后网络的分类准确性降低（CAR）。然后基于CAR索引迭代地修剪滤波器。我们通过显示我们的算法修剪过滤器的视觉冗余模式选择性来证明CAR压缩的CNN的可解释性。具体来说，我们展示了形状选择滤波器对物体识别的重要性，而不是色彩选择滤波器。在AlexNet的前20个CAR-修剪过滤器中，第一层中的17个和第二层中的14个是颜色选择性过滤器。最后，我们引入CAR重要性指数的变体，量化每个图像类别对每个CNN滤波器的重要性。我们展示了最重要的和最不重要的类标签对每个过滤器提供了一个有意义的解释，该过滤器与该过滤器的可视化图案选择性一致。

##### URL
[https://arxiv.org/abs/1711.02329](https://arxiv.org/abs/1711.02329)

##### PDF
[https://arxiv.org/pdf/1711.02329](https://arxiv.org/pdf/1711.02329)

