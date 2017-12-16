---
layout: post
title: "Ensemble of Part Detectors for Simultaneous Classification and Localization"
date: 2017-05-29 04:04:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Sparse Image_Classification Classification Detection
author: Xiaopeng Zhang, Hongkai Xiong, Weiyao Lin, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Part-based representation has been proven to be effective for a variety of visual applications. However, automatic discovery of discriminative parts without object/part-level annotations is challenging. This paper proposes a discriminative mid-level representation paradigm based on the responses of a collection of part detectors, which only requires the image-level labels. Towards this goal, we first develop a detector-based spectral clustering method to mine the representative and discriminative mid-level patterns for detector initialization. The advantage of the proposed pattern mining technology is that the distance metric based on detectors only focuses on discriminative details, and a set of such grouped detectors offer an effective way for consistent pattern mining. Relying on the discovered patterns, we further formulate the detector learning process as a confidence-loss sparse Multiple Instance Learning (cls-MIL) task, which considers the diversity of the positive samples, while avoid drifting away the well localized ones by assigning a confidence value to each positive sample. The responses of the learned detectors can form an effective mid-level image representation for both image classification and object localization. Experiments conducted on benchmark datasets demonstrate the superiority of our method over existing approaches.

##### Abstract (translated by Google)
已经证明基于部件的表示对于各种视觉应用是有效的。但是，自动发现没有对象/部分级别注释的判别性部分是具有挑战性的。本文提出了一个基于部分检测器集合的响应的判别式中间表示范式，它只需要图像级标签。为了实现这一目标，我们首先开发了一种基于探测器的谱聚类方法来挖掘有代表性和判别性的中等水平模式，用于探测器的初始化。所提出的模式挖掘技术的优点在于，基于检测器的距离度量仅关注区分细节，一组这样的分组检测器为一致模式挖掘提供了一种有效的方法。依靠所发现的模式，我们进一步将检测器学习过程制定为考虑到正样本的多样性的置信稀疏多重实例学习（CIs-MIL）任务，同时通过分配置信度避免偏离定位好的样本对每个正面样本的价值。学习的检测器的响应可以形成用于图像分类和对象定位的有效中间级图像表示。在基准数据集上进行的实验证明了我们的方法优于现有的方法。

##### URL
[https://arxiv.org/abs/1705.10034](https://arxiv.org/abs/1705.10034)

##### PDF
[https://arxiv.org/pdf/1705.10034](https://arxiv.org/pdf/1705.10034)

