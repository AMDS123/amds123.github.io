---
layout: post
title: "Deep Motif Dashboard: Visualizing and Understanding Genomic Sequences Using Deep Neural Networks"
date: 2016-10-18 20:20:22
categories: arXiv_CV
tags: arXiv_CV Salient CNN Optimization RNN Classification Prediction
author: Jack Lanchantin, Ritambhara Singh, Beilun Wang, Yanjun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network (DNN) models have recently obtained state-of-the-art prediction accuracy for the transcription factor binding (TFBS) site classification task. However, it remains unclear how these approaches identify meaningful DNA sequence signals and give insights as to why TFs bind to certain locations. In this paper, we propose a toolkit called the Deep Motif Dashboard (DeMo Dashboard) which provides a suite of visualization strategies to extract motifs, or sequence patterns from deep neural network models for TFBS classification. We demonstrate how to visualize and understand three important DNN models: convolutional, recurrent, and convolutional-recurrent networks. Our first visualization method is finding a test sequence's saliency map which uses first-order derivatives to describe the importance of each nucleotide in making the final prediction. Second, considering recurrent models make predictions in a temporal manner (from one end of a TFBS sequence to the other), we introduce temporal output scores, indicating the prediction score of a model over time for a sequential input. Lastly, a class-specific visualization strategy finds the optimal input sequence for a given TFBS positive class via stochastic gradient optimization. Our experimental results indicate that a convolutional-recurrent architecture performs the best among the three architectures. The visualization techniques indicate that CNN-RNN makes predictions by modeling both motifs as well as dependencies among them.

##### Abstract (translated by Google)
深度神经网络（DNN）模型最近获得了转录因子结合（TFBS）位点分类任务的最新预测精度。然而，目前还不清楚这些方法如何鉴定有意义的DNA序列信号，并对TFs为何与某些位置结合提供见解。在本文中，我们提出了一个名为Deep Motif Dashboard（DeMo Dashboard）的工具箱，它提供了一套可视化策略来从TFBS分类的深层神经网络模型中提取图案或序列模式。我们演示如何可视化和理解三个重要的DNN模型：卷积，循环和卷积循环网络。我们的第一个可视化方法是找到一个测试序列的显着图，它使用一阶导数来描述每个核苷酸在进行最终预测中的重要性。其次，考虑到经常性模型以时间的方式（从TFBS序列的一端到另一端）进行预测，我们引入时间输出分数，表示连续输入随时间变化的模型的预测分数。最后，一个类特定的可视化策略通过随机梯度优化找到给定的TFBS正类的最优输入序列。我们的实验结果表明，卷积循环体系结构在三种体系结构中表现最好。可视化技术表明CNN-RNN通过对两个图案以及它们之间的依赖性进行建模来进行预测。

##### URL
[https://arxiv.org/abs/1608.03644](https://arxiv.org/abs/1608.03644)

##### PDF
[https://arxiv.org/pdf/1608.03644](https://arxiv.org/pdf/1608.03644)

