---
layout: post
title: "Learning Document Image Binarization from Data"
date: 2015-05-04 05:57:17
categories: arXiv_CV
tags: arXiv_CV
author: Yue Wu, Stephen Rawls, Wael AbdAlmageed, Premkumar Natarajan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a fully trainable binarization solution for degraded document images. Unlike previous attempts that often used simple features with a series of pre- and post-processing, our solution encodes all heuristics about whether or not a pixel is foreground text into a high-dimensional feature vector and learns a more complicated decision function. In particular, we prepare features of three types: 1) existing features for binarization such as intensity [1], contrast [2], [3], and Laplacian [4], [5]; 2) reformulated features from existing binarization decision functions such those in [6] and [7]; and 3) our newly developed features, namely the Logarithm Intensity Percentile (LIP) and the Relative Darkness Index (RDI). Our initial experimental results show that using only selected samples (about 1.5% of all available training data), we can achieve a binarization performance comparable to those fine-tuned (typically by hand), state-of-the-art methods. Additionally, the trained document binarization classifier shows good generalization capabilities on out-of-domain data.

##### Abstract (translated by Google)
在本文中，我们提出了一个完全可训练的退化文档图像的二值化解决方案。与之前的一些经常使用简单特征和前后处理的尝试不同，我们的解决方案将关于像素是否为前景文本的所有启发式都编码为高维特征向量，并学习更复杂的决策函数。特别地，我们准备了三种类型的特征：1）二值化的现有特征，如强度[1]，对比[2]，[3]和拉普拉斯[4]，[5]; 2）现有二值化决策函数的重新表达特征[6]和[7];和3）我们新开发的特征，即对数强度百分位数（LIP）和相对黑度指数（RDI）。我们最初的实验结果表明，只使用选定的样本（大约1.5％的所有可用训练数据），我们可以实现与那些经过精细调整（通常是手工）的先进方法相媲美的二值化性能。另外，经过训练的文档二值化分类器对于域外数据显示出良好的泛化能力。

##### URL
[https://arxiv.org/abs/1505.00529](https://arxiv.org/abs/1505.00529)

##### PDF
[https://arxiv.org/pdf/1505.00529](https://arxiv.org/pdf/1505.00529)

