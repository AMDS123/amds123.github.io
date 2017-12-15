---
layout: post
title: "Image Super-resolution via Feature-augmented Random Forest"
date: 2017-12-14 14:27:39
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Super_Resolution
author: Hailiang Li, Kin-Man Lam, Miaohui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent random-forest (RF)-based image super-resolution approaches inherit some properties from dictionary-learning-based algorithms, but the effectiveness of the properties in RF is overlooked in the literature. In this paper, we present a novel feature-augmented random forest (FARF) for image super-resolution, where the conventional gradient-based features are augmented with gradient magnitudes and different feature recipes are formulated on different stages in an RF. The advantages of our method are that, firstly, the dictionary-learning-based features are enhanced by adding gradient magnitudes, based on the observation that the non-linear gradient magnitude are with highly discriminative property. Secondly, generalized locality-sensitive hashing (LSH) is used to replace principal component analysis (PCA) for feature dimensionality reduction and original high-dimensional features are employed, instead of the compressed ones, for the leaf-nodes' regressors, since regressors can benefit from higher dimensional features. This original-compressed coupled feature sets scheme unifies the unsupervised LSH evaluation on both image super-resolution and content-based image retrieval (CBIR). Finally, we present a generalized weighted ridge regression (GWRR) model for the leaf-nodes' regressors. Experiment results on several public benchmark datasets show that our FARF method can achieve an average gain of about 0.3 dB, compared to traditional RF-based methods. Furthermore, a fine-tuned FARF model can compare to or (in many cases) outperform some recent stateof-the-art deep-learning-based algorithms.

##### Abstract (translated by Google)
最近基于随机森林（RF）的图像超分辨率方法继承了字典学习算法的一些性质，但文献中忽略了RF性质的有效性。在本文中，我们提出了一种新的用于图像超分辨率的特征增强随机森林（FARF），其中常规的基于梯度的特征增加了梯度幅度，并且在RF中的不同阶段制定了不同的特征配方。我们的方法的优点是，首先，基于非线性梯度幅度具有高度判别性的观察，通过添加梯度幅度来增强基于字典学习的特征。其次，采用广义局部敏感哈希（LSH）替代主成分分析（PCA）进行特征降维，而对叶节点回归机采用原始高维特征而不是压缩后的特征，因为回归机受益于更高的尺寸特征。这种原始压缩的耦合特征集方案统一了无监督LSH评估对图像超分辨率和基于内容的图像检索（CBIR）。最后，我们提出叶节点回归的广义加权岭回归（GWRR）模型。在几个公共基准数据集上的实验结果表明，与传统的基于RF的方法相比，我们的FARF方法可以实现约0.3dB的平均增益。此外，经过微调的FARF模型可以比较或者（在许多情况下）优于最近的一些最新的基于深度学习的算法。

##### URL
[http://arxiv.org/abs/1712.05248](http://arxiv.org/abs/1712.05248)

##### PDF
[http://arxiv.org/pdf/1712.05248](http://arxiv.org/pdf/1712.05248)

