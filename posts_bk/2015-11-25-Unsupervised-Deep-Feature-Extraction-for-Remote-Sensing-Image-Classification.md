---
layout: post
title: "Unsupervised Deep Feature Extraction for Remote Sensing Image Classification"
date: 2015-11-25 17:36:28
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Image_Classification Classification
author: Adriana Romero, Carlo Gatta, Gustau Camps-Valls
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the use of single layer and deep convolutional networks for remote sensing data analysis. Direct application to multi- and hyper-spectral imagery of supervised (shallow or deep) convolutional networks is very challenging given the high input data dimensionality and the relatively small amount of available labeled data. Therefore, we propose the use of greedy layer-wise unsupervised pre-training coupled with a highly efficient algorithm for unsupervised learning of sparse features. The algorithm is rooted on sparse representations and enforces both population and lifetime sparsity of the extracted features, simultaneously. We successfully illustrate the expressive power of the extracted representations in several scenarios: classification of aerial scenes, as well as land-use classification in very high resolution (VHR), or land-cover classification from multi- and hyper-spectral images. The proposed algorithm clearly outperforms standard Principal Component Analysis (PCA) and its kernel counterpart (kPCA), as well as current state-of-the-art algorithms of aerial classification, while being extremely computationally efficient at learning representations of data. Results show that single layer convolutional networks can extract powerful discriminative features only when the receptive field accounts for neighboring pixels, and are preferred when the classification requires high resolution and detailed results. However, deep architectures significantly outperform single layers variants, capturing increasing levels of abstraction and complexity throughout the feature hierarchy.

##### Abstract (translated by Google)
本文介绍了利用单层和深度卷积网络进行遥感数据分析。考虑到高输入数据维度和相对少量的可用标记数据，直接应用于监督（浅或深）卷积网络的多光谱和超光谱图像是非常具有挑战性的。因此，我们提出使用贪心分层无监督预训练与高效的算法相结合，实现稀疏特征的无监督学习。该算法根植于稀疏表示，同时强化提取特征的种群和生命稀疏度。我们在几个场景中成功地说明了提取的表示的表达能力：空中场景的分类，甚高分辨率（VHR）的土地利用分类，或者多光谱图像和高光谱图像的土地覆盖分类。所提出的算法明显优于标准主成分分析（PCA）及其内核对应（kPCA），以及当前最先进的航空分类算法，同时在学习数据表示方面具有极高的计算效率。结果表明，单层卷积网络只能在接收场占用相邻像素的情况下才能提取出较强的判别性特征，在分类需要高分辨率和细致的结果时较好。但是，深层体系结构明显优于单层变体，在整个功能层次中捕获越来越高的抽象层次和复杂性。

##### URL
[https://arxiv.org/abs/1511.08131](https://arxiv.org/abs/1511.08131)

##### PDF
[https://arxiv.org/pdf/1511.08131](https://arxiv.org/pdf/1511.08131)

