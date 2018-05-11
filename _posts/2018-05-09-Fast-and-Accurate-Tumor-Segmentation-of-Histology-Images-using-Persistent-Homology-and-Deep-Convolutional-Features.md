---
layout: post
title: "Fast and Accurate Tumor Segmentation of Histology Images using Persistent Homology and Deep Convolutional Features"
date: 2018-05-09 19:02:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Talha Qaiser, Yee-Wah Tsang, Daiki Taniyama, Naoya Sakamoto, Kazuaki Nakane, David Epstein, Nasir Rajpoot
mathjax: true
---

* content
{:toc}

##### Abstract
Tumor segmentation in whole-slide images of histology slides is an important step towards computer-assisted diagnosis. In this work, we propose a tumor segmentation framework based on the novel concept of persistent homology profiles (PHPs). For a given image patch, the homology profiles are derived by efficient computation of persistent homology, which is an algebraic tool from homology theory. We propose an efficient way of computing topological persistence of an image, alternative to simplicial homology. The PHPs are devised to distinguish tumor regions from their normal counterparts by modeling the atypical characteristics of tumor nuclei. We propose two variants of our method for tumor segmentation: one that targets speed without compromising accuracy and the other that targets higher accuracy. The fast version is based on the selection of exemplar image patches from a convolution neural network (CNN) and patch classification by quantifying the divergence between the PHPs of exemplars and the input image patch. Detailed comparative evaluation shows that the proposed algorithm is significantly faster than competing algorithms while achieving comparable results. The accurate version combines the PHPs and high-level CNN features and employs a multi-stage ensemble strategy for image patch labeling. Experimental results demonstrate that the combination of PHPs and CNN features outperforms competing algorithms. This study is performed on two independently collected colorectal datasets containing adenoma, adenocarcinoma, signet and healthy cases. Collectively, the accurate tumor segmentation produces the highest average patch-level F1-score, as compared with competing algorithms, on malignant and healthy cases from both the datasets. Overall the proposed framework highlights the utility of persistent homology for histopathology image analysis.

##### Abstract (translated by Google)
在组织学幻灯片的全幻灯片图像中的肿瘤分割是朝向计算机辅助诊断迈出的重要一步。在这项工作中，我们提出了一个基于持久同源配置文件（PHP）的新概念的肿瘤分割框架。对于给定的图像片段，通过有效计算持久同源性来获得同源性谱，其是来自同源性理论的代数工具。我们提出一种计算图像拓扑持久性的有效方法，替代单纯的同源。通过对肿瘤细胞核的非典型特征进行建模，PHP设计为将肿瘤区域与正常细胞区分开来。我们提出了两种肿瘤分割方法的变体：一种是在不影响准确性的情况下以速度为目标，另一种以更高精度为目标。快速版基于从卷积神经网络（CNN）选择示例图像块并通过量化样本的PHP与输入图像块之间的差异来进行补丁分类。详细的比较评估表明，所提出的算法比竞争算法快得多，同时实现可比较的结果。准确的版本结合了PHP和高级CNN功能，并采用多阶段集成策略进行图像补丁标签。实验结果表明，PHP和CNN功能的组合优于竞争算法。本研究是在两个独立收集的包含腺瘤，腺癌，印章和健康案例的结直肠数据集上进行的。总体而言，与竞争算法相比，准确的肿瘤分割产生的平均斑块水平F1分数对于来自两个数据集的恶性和健康病例均是最高的。总体而言，所提出的框架强调了用于组织病理学图像分析的持久同源性的效用。

##### URL
[http://arxiv.org/abs/1805.03699](http://arxiv.org/abs/1805.03699)

##### PDF
[http://arxiv.org/pdf/1805.03699](http://arxiv.org/pdf/1805.03699)

