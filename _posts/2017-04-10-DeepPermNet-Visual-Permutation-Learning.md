---
layout: post
title: "DeepPermNet: Visual Permutation Learning"
date: 2017-04-10 06:59:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Represenation_Learning Classification Deep_Learning Prediction
author: Rodrigo Santa Cruz, Basura Fernando, Anoop Cherian, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
We present a principled approach to uncover the structure of visual data by solving a novel deep learning task coined visual permutation learning. The goal of this task is to find the permutation that recovers the structure of data from shuffled versions of it. In the case of natural images, this task boils down to recovering the original image from patches shuffled by an unknown permutation matrix. Unfortunately, permutation matrices are discrete, thereby posing difficulties for gradient-based methods. To this end, we resort to a continuous approximation of these matrices using doubly-stochastic matrices which we generate from standard CNN predictions using Sinkhorn iterations. Unrolling these iterations in a Sinkhorn network layer, we propose DeepPermNet, an end-to-end CNN model for this task. The utility of DeepPermNet is demonstrated on two challenging computer vision problems, namely, (i) relative attributes learning and (ii) self-supervised representation learning. Our results show state-of-the-art performance on the Public Figures and OSR benchmarks for (i) and on the classification and segmentation tasks on the PASCAL VOC dataset for (ii).

##### Abstract (translated by Google)
我们提出了一个原则性的方法来揭示视觉数据的结构，通过解决一个新的深度学习任务创造视觉排列学习。这个任务的目标是找到从它的混洗版本中恢复数据结构的排列组合。在自然图像的情况下，这个任务归结为从由未知置换矩阵洗牌的补丁恢复原始图像。不幸的是，置换矩阵是离散的，从而给基于梯度的方法带来困难。为此，我们使用双随机矩阵对这些矩阵进行连续逼近，这些矩阵是使用Sinkhorn迭代从标准CNN预测中产生的。在Sinkhorn网络层展开这些迭代，我们提出DeepPermNet，这是一个端到端的CNN模型。 DeepPermNet的实用性表现在两个具有挑战性的计算机视觉问题上，即（i）相对属性学习和（ii）自我监督表示学习。我们的研究结果显示了（i）的公共数据和OSR基准以及（ii）的PASCAL VOC数据集上的分类和分割任务的最新性能。

##### URL
[https://arxiv.org/abs/1704.02729](https://arxiv.org/abs/1704.02729)

##### PDF
[https://arxiv.org/pdf/1704.02729](https://arxiv.org/pdf/1704.02729)

