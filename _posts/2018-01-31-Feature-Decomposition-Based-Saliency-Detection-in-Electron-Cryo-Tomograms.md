---
layout: post
title: "Feature Decomposition Based Saliency Detection in Electron Cryo-Tomograms"
date: 2018-01-31 17:25:14
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Detection Recognition
author: Bo Zhou, Qiang Guo, Xiangrui Zeng, Min Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Electron Cryo-Tomography (ECT) allows 3D visualization of subcellular structures at the submolecular resolution in close to the native state. However, due to the high degree of structural complexity and imaging limits, the automatic segmentation of cellular components from ECT images is very difficult. To complement and speed up existing segmentation methods, it is desirable to develop a generic cell component segmentation method that is 1) not specific to particular types of cellular components, 2) able to segment unknown cellular components, 3) fully unsupervised and does not rely on the availability of training data. As an important step towards this goal, in this paper, we propose a saliency detection method that computes the likelihood that a subregion in a tomogram stands out from the background. Our method consists of four steps: supervoxel over-segmentation, feature extraction, feature matrix decomposition, and computation of saliency. The method produces a distribution map that represents the regions' saliency in tomograms. Our experiments show that our method can successfully label most salient regions detected by a human observer, and able to filter out regions not containing cellular components. Therefore, our method can remove the majority of the background region, and significantly speed up the subsequent processing of segmentation and recognition of cellular components captured by ECT.

##### Abstract (translated by Google)
电子冷冻层析成像（ECT）允许以接近天然状态的分子分辨率对亚细胞结构进行三维可视化。然而，由于结构复杂性和成像极限的高度，从ECT图像自动分割细胞成分是非常困难的。为了补充和加速现有的分割方法，需要开发一种通用的细胞成分分割方法，该方法1）不特定于特定类型的细胞成分，2）能够分割未知的细胞成分，3）完全无监督，不依赖于关于培训数据的可用性。作为实现这一目标的一个重要步骤，本文中，我们提出了一种显着性检测方法，用于计算层析图中的子区域从背景中脱颖而出的可能性。我们的方法由四个步骤组成：超体素超分割，特征提取，特征矩阵分解和显着性计算。该方法生成一个分布图，表示区域在X线断层图中的显着性。我们的实验表明，我们的方法可以成功地标记人类观察者检测到的大多数显着区域，并能够过滤掉不含细胞成分的区域。因此，我们的方法可以去除大部分的背景区域，并显着加快了ECT捕获的细胞成分的分割和识别的后续处理。

##### URL
[http://arxiv.org/abs/1801.10562](http://arxiv.org/abs/1801.10562)

##### PDF
[http://arxiv.org/pdf/1801.10562](http://arxiv.org/pdf/1801.10562)

