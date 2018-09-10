---
layout: post
title: "Using Trusted Data to Train Deep Networks on Labels Corrupted by Severe Noise"
date: 2018-09-06 19:07:19
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Dan Hendrycks, Mantas Mazeika, Duncan Wilson, Kevin Gimpel
mathjax: true
---

* content
{:toc}

##### Abstract
The growing importance of massive datasets with the advent of deep learning makes robustness to label noise a critical property for classifiers to have. Sources of label noise include automatic labeling for large datasets, non-expert labeling, and label corruption by data poisoning adversaries. In the latter case, corruptions may be arbitrarily bad, even so bad that a classifier predicts the wrong labels with high confidence. To protect against such sources of noise, we leverage the fact that a small set of clean labels is often easy to procure. We demonstrate that robustness to label noise up to severe strengths can be achieved by using a set of trusted data with clean labels, and propose a loss correction that utilizes trusted examples in a data-efficient manner to mitigate the effects of label noise on deep neural network classifiers. Across vision and natural language processing tasks, we experiment with various label noises at several strengths, and show that our method significantly outperforms existing methods.

##### Abstract (translated by Google)
随着深度学习的出现，大规模数据集的重要性日益增加，这使得标记噪声的鲁棒性成为分类器的关键属性。标签噪声的来源包括大数据集的自动标记，非专家标签以及数据中毒对手的标签损坏。在后一种情况下，腐败可能是任意不好的，甚至是如此糟糕以至于分类器以高置信度预测错误的标签。为了防止这些噪音源，我们利用了一小部分清洁标签通常很容易获得的事实。我们证明，通过使用一组带有干净标签的可信数据，可以实现标签噪声达到严重强度的稳健性，并提出一种损失修正，利用数据有效方式的可信示例来减轻标签噪声对深度神经的影响网络分类器。在视觉和自然语言处理任务中，我们尝试了多种强度的各种标签噪声，并表明我们的方法明显优于现有方法。

##### URL
[http://arxiv.org/abs/1802.05300](http://arxiv.org/abs/1802.05300)

##### PDF
[http://arxiv.org/pdf/1802.05300](http://arxiv.org/pdf/1802.05300)

