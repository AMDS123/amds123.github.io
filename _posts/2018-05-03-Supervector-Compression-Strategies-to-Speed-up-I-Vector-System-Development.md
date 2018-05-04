---
layout: post
title: "Supervector Compression Strategies to Speed up I-Vector System Development"
date: 2018-05-03 08:12:39
categories: arXiv_CL
tags: arXiv_CL
author: Ville Vestman, Tomi Kinnunen
mathjax: true
---

* content
{:toc}

##### Abstract
The front-end factor analysis (FEFA), an extension of principal component analysis (PPCA) tailored to be used with Gaussian mixture models (GMMs), is currently the prevalent approach to extract compact utterance-level features (i-vectors) for automatic speaker verification (ASV) systems. Little research has been conducted comparing FEFA to the conventional PPCA applied to maximum a posteriori (MAP) adapted GMM supervectors. We study several alternative methods, including PPCA, factor analysis (FA), and two supervised approaches, supervised PPCA (SPPCA) and the recently proposed probabilistic partial least squares (PPLS), to compress MAP-adapted GMM supervectors. The resulting i-vectors are used in ASV tasks with a probabilistic linear discriminant analysis (PLDA) back-end. We experiment on two different datasets, on the telephone condition of NIST SRE 2010 and on the recent VoxCeleb corpus collected from YouTube videos containing celebrity interviews recorded in various acoustical and technical conditions. The results suggest that, in terms of ASV accuracy, the supervector compression approaches are on a par with FEFA. The supervised approaches did not result in improved performance. In comparison to FEFA, we obtained more than hundred-fold (100x) speedups in the total variability model (TVM) training using the PPCA and FA supervector compression approaches.

##### Abstract (translated by Google)
前端因素分析（FEFA）是适用于高斯混合模型（GMMs）的主成分分析（PPCA）的扩展，目前是用于自动提取紧凑话语水平特征（i向量）的普遍方法说话人验证（ASV）系统。很少有研究将FEFA与应用于最大后验（MAP）适应GMM超向量的常规PPCA进行比较。我们研究了几种替代方法，包括PPCA，因子分析（FA）和两种监督方法，监督PPCA（SPPCA）和最近提出的概率偏最小二乘法（PPLS），以压缩MAP适应的GMM超向量。所得到的i矢量用于具有概率线性判别分析（PLDA）后端的ASV任务。我们在两个不同的数据集上进行实验，包括NIST SRE 2010的电话条件以及最近从YouTube视频中收集的最近的VoxCeleb语料库，其中包含在各种声学和技术条件下记录的名人访谈。结果表明，就ASV精度而言，超矢量压缩方法与FEFA相当。受监督的方法并没有改善绩效。与FEFA相比，我们在使用PPCA和FA超矢量压缩方法的总变异性模型（TVM）训练中获得超过100倍（100x）的加速。

##### URL
[http://arxiv.org/abs/1805.01156](http://arxiv.org/abs/1805.01156)

##### PDF
[http://arxiv.org/pdf/1805.01156](http://arxiv.org/pdf/1805.01156)

