---
layout: post
title: "Robust Scene Text Recognition Using Sparse Coding based Features"
date: 2015-12-29 12:50:40
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Detection Recognition
author: Da-Han Wang, Hanzi Wang, Dong Zhang, Jonathan Li, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an effective scene text recognition method using sparse coding based features, called Histograms of Sparse Codes (HSC) features. For character detection, we use the HSC features instead of using the Histograms of Oriented Gradients (HOG) features. The HSC features are extracted by computing sparse codes with dictionaries that are learned from data using K-SVD, and aggregating per-pixel sparse codes to form local histograms. For word recognition, we integrate multiple cues including character detection scores and geometric contexts in an objective function. The final recognition results are obtained by searching for the words which correspond to the maximum value of the objective function. The parameters in the objective function are learned using the Minimum Classification Error (MCE) training method. Experiments on several challenging datasets demonstrate that the proposed HSC-based scene text recognition method outperforms HOG-based methods significantly and outperforms most state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于稀疏编码的特征的有效场景文本识别方法，称为稀疏编码（Histogram of Sparse Codes，HSC）特征。对于字符检测，我们使用HSC功能，而不是使用面向方向梯度（HOG）功能的直方图。通过使用K-SVD从数据中学习的字典计算稀疏代码并聚合每像素稀疏代码以形成局部直方图来提取HSC特征。对于单词识别，我们将多个提示包括字符检测分数和几何背景集成在一个目标函数中。最终的识别结果是通过搜索与目标函数的最大值对应的字来获得的。目标函数中的参数是使用最小分类错误（MCE）训练方法学习的。对几个具有挑战性的数据集进行的实验表明，所提出的基于HSC的场景文本识别方法明显优于基于HOG的方法，并且胜过大多数最新的方法。

##### URL
[https://arxiv.org/abs/1512.08669](https://arxiv.org/abs/1512.08669)

##### PDF
[https://arxiv.org/pdf/1512.08669](https://arxiv.org/pdf/1512.08669)

