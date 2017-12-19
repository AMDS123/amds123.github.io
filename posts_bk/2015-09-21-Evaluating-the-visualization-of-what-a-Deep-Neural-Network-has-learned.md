---
layout: post
title: "Evaluating the visualization of what a Deep Neural Network has learned"
date: 2015-09-21 17:36:22
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Image_Classification Classification Quantitative Recognition
author: Wojciech Samek, Alexander Binder, Grégoire Montavon, Sebastian Bach, Klaus-Robert Müller
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have demonstrated impressive performance in complex machine learning tasks such as image classification or speech recognition. However, due to their multi-layer nonlinear structure, they are not transparent, i.e., it is hard to grasp what makes them arrive at a particular classification or recognition decision given a new unseen data sample. Recently, several approaches have been proposed enabling one to understand and interpret the reasoning embodied in a DNN for a single test image. These methods quantify the ''importance'' of individual pixels wrt the classification decision and allow a visualization in terms of a heatmap in pixel/input space. While the usefulness of heatmaps can be judged subjectively by a human, an objective quality measure is missing. In this paper we present a general methodology based on region perturbation for evaluating ordered collections of pixels such as heatmaps. We compare heatmaps computed by three different methods on the SUN397, ILSVRC2012 and MIT Places data sets. Our main result is that the recently proposed Layer-wise Relevance Propagation (LRP) algorithm qualitatively and quantitatively provides a better explanation of what made a DNN arrive at a particular classification decision than the sensitivity-based approach or the deconvolution method. We provide theoretical arguments to explain this result and discuss its practical implications. Finally, we investigate the use of heatmaps for unsupervised assessment of neural network performance.

##### Abstract (translated by Google)
深度神经网络（DNN）在复杂的机器学习任务（如图像分类或语音识别）中表现出令人印象深刻的性能。然而，由于它们的多层非线性结构，它们是不透明的，即在给定新的看不见的数据样本的情况下难以掌握使它们到达特定分类或识别决定的原因。最近，已经提出了多种方法，使得能够理解和解释用于单个测试图像的DNN中包含的推理。这些方法量化了单个像素对于分类决定的“重要性”，并允许在像素/输入空间中的热图的可视化。虽然热图的有用性可以由人的主观判断，但客观的质量指标缺失。在本文中，我们提出了一个基于区域摄动的一般方法，用于评估像素的有序集合，如热图。我们比较SUN397，ILSVRC2012和MIT Places数据集上三种不同方法计算的热点图。我们的主要结果是最近提出的分层相关传播（LRP）算法定性和定量地提供了一个更好的解释是什么使DNN达到特定的分类决定比基于灵敏度的方法或去卷积方法。我们提供理论依据来解释这个结果并讨论它的实际含义。最后，我们调查热图的使用神经网络性能的无监督评估。

##### URL
[https://arxiv.org/abs/1509.06321](https://arxiv.org/abs/1509.06321)

##### PDF
[https://arxiv.org/pdf/1509.06321](https://arxiv.org/pdf/1509.06321)

