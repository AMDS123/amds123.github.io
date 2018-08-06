---
layout: post
title: "CurriculumNet: Weakly Supervised Learning from Large-Scale Web Images"
date: 2018-08-03 06:42:11
categories: arXiv_CV
tags: arXiv_CV Regularization Weakly_Supervised Classification
author: Sheng Guo, Weilin Huang, Haozhi Zhang, Chenfan Zhuang, Dengke Dong, Matthew R. Scott, Dinglong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple yet efficient approach capable of training deep neural networks on large-scale weakly-supervised web images, which are crawled rawly from the Internet by using text queries, without any human annotation. We develop a principled learning strategy by leveraging curriculum learning, with the goal of handling massive amount of noisy labels and data imbalance effectively. We design a new learning curriculum by measuring the complexity of data using its distribution density in a feature space, and rank the complexity in an unsupervised manner. This allows for an efficient implementation of curriculum learning on large-scale web images, resulting in a high-performance CNN model, where the negative impact of noisy labels is reduced substantially. Importantly, we show by experiments that those images with highly noisy labels can surprisingly improve the generalization capability of model, by serving as a manner of regularization. Our approaches obtain the state-of-the-art performance on four benchmarks, including Webvision, ImageNet, Clothing-1M and Food-101. With an ensemble of multiple models, we achieve a top-5 error rate of 5.2% on the Webvision challenge for 1000-category classification, which is the top performance that surpasses other results by a large margin of about 50% relative error rate. Codes and models are available at: https://github.com/guoshengcv/CurriculumNet.

##### Abstract (translated by Google)
我们提出了一种简单而有效的方法，能够在大规模的弱监督网络图像上训练深度神经网络，这些网络图像通过使用文本查询从互联网上原始爬行，无需任何人工注释。我们通过利用课程学习制定原则性学习策略，目标是有效处理大量噪音标签和数据不平衡。我们通过在特征空间中使用其分布密度来测量数据的复杂性来设计新的学习课程，并以无人监督的方式对复杂性进行排序。这允许在大规模网络图像上有效地实施课程学习，从而产生高性能CNN模型，其中嘈杂标签的负面影响显着降低。重要的是，我们通过实验表明，具有高噪声标签的图像可以令人惊讶地通过用作正则化方式来改善模型的泛化能力。我们的方法在四个基准测试中获得了最先进的性能，包括Webvision，ImageNet，Clothing-1M和Food-101。通过多个模型的集合，我们在1000类别分类的Webvision挑战中实现了5.2％的前5个错误率，这是超过其他结果的最高性能，相对错误率大约为50％。代码和模型可从以下网址获得：https：//github.com/guoshengcv/CurriculumNet。

##### URL
[http://arxiv.org/abs/1808.01097](http://arxiv.org/abs/1808.01097)

##### PDF
[http://arxiv.org/pdf/1808.01097](http://arxiv.org/pdf/1808.01097)

