---
layout: post
title: "Using Trusted Data to Train Deep Networks on Labels Corrupted by Severe Noise"
date: 2018-02-14 19:48:50
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
随着深度学习的出现，海量数据集越来越重要，这使得标签噪声的稳健性成为分类器的关键属性。标签噪音的来源包括大数据集的自动标签，非专家标签以及数据中毒对手的标签腐败。在后一种情况下，腐败可能是任意坏的，甚至很糟糕，以至于分类器以高置信度预测错误的标签。为了防止这些噪音源，我们利用这样一个事实，即一小组清洁标签通常很容易获得。我们证明，通过使用干净标签的一组可信数据，可以实现标签噪声达到严重强度的稳健性，并提出一种损失校正方法，以数据有效的方式利用可信实例来减轻标签噪声对深度神经的影响网络分类器。在视觉和自然语言处理任务中，我们以各种优势试验各种标签噪音，并表明我们的方法明显优于现有方法。

##### URL
[https://arxiv.org/abs/1802.05300](https://arxiv.org/abs/1802.05300)

##### PDF
[https://arxiv.org/pdf/1802.05300](https://arxiv.org/pdf/1802.05300)

