---
layout: post
title: "Feature Transfer Learning for Deep Face Recognition with Long-Tail Data"
date: 2018-03-23 23:37:31
categories: arXiv_CV
tags: arXiv_CV Face Transfer_Learning Recognition Face_Recognition
author: Xi Yin, Xiang Yu, Kihyuk Sohn, Xiaoming Liu, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world face recognition datasets exhibit long-tail characteristics, which results in biased classifiers in conventionally-trained deep neural networks, or insufficient data when long-tail classes are ignored. In this paper, we propose to handle long-tail classes in the training of a face recognition engine by augmenting their feature space under a center-based feature transfer framework. A Gaussian prior is assumed across all the head (regular) classes and the variance from regular classes are transferred to the long-tail class representation. This encourages the long-tail distribution to be closer to the regular distribution, while enriching and balancing the limited training data. Further, an alternating training regimen is proposed to simultaneously achieve less biased decision boundaries and a more discriminative feature representation. We conduct empirical studies that mimic long-tail datasets by limiting the number of samples and the proportion of long-tail classes on the MS-Celeb-1M dataset. We compare our method with baselines not designed to handle long-tail classes and also with state-of-the-art methods on face recognition benchmarks. State-of-the-art results on LFW, IJB-A and MS-Celeb-1M datasets demonstrate the effectiveness of our feature transfer approach and training strategy. Finally, our feature transfer allows smooth visual interpolation, which demonstrates disentanglement to preserve identity of a class while augmenting its feature space with non-identity variations.

##### Abstract (translated by Google)
真实世界的人脸识别数据集呈现出长尾特征，这会导致传统训练的深度神经网络中存在偏向分类器，或者在忽略长尾类时数据不足。在本文中，我们建议通过在基于中心的特征传输框架下增加特征空间来处理长尾类别训练中的人脸识别引擎。在所有头（常规）类中假设高斯先验，并且将来自常规类的方差转移到长尾类表示。这鼓励了长尾分布更接近正常分布，同时丰富和平衡有限的训练数据。此外，提出了交替训练方案，以同时实现较少偏倚的决策边界和更具辨别性的特征表示。我们通过限制MS-Celeb-1M数据集中样本的数量和长尾类的比例来进行模仿长尾数据集的实证研究。我们将我们的方法与未设计用于处理长尾类的基线以及人脸识别基准中的最新方法进行比较。 LFW，IJB-A和MS-Celeb-1M数据集的最新成果证明了我们的特征传输方法和培训策略的有效性。最后，我们的特征转移允许平滑的视觉插值，这展示了解缠以保持类的身份，同时用非身份变体增强其特征空间。

##### URL
[https://arxiv.org/abs/1803.09014](https://arxiv.org/abs/1803.09014)

##### PDF
[https://arxiv.org/pdf/1803.09014](https://arxiv.org/pdf/1803.09014)

