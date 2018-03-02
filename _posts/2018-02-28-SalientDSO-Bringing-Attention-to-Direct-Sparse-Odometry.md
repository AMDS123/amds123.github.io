---
layout: post
title: "SalientDSO: Bringing Attention to Direct Sparse Odometry"
date: 2018-02-28 23:02:47
categories: arXiv_CV
tags: arXiv_CV Salient Sparse Knowledge Attention Optimization Deep_Learning Quantitative SLAM
author: Huai-Jen Liang, Nitin J. Sanket, Cornelia Ferm&#xfc;ller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
Although cluttered indoor scenes have a lot of useful high-level semantic information which can be used for mapping and localization, most Visual Odometry (VO) algorithms rely on the usage of geometric features such as points, lines and planes. Lately, driven by this idea, the joint optimization of semantic labels and obtaining odometry has gained popularity in the robotics community. The joint optimization is good for accurate results but is generally very slow. At the same time, in the vision community, direct and sparse approaches for VO have stricken the right balance between speed and accuracy. 
 We merge the successes of these two communities and present a way to incorporate semantic information in the form of visual saliency to Direct Sparse Odometry - a highly successful direct sparse VO algorithm. We also present a framework to filter the visual saliency based on scene parsing. Our framework, SalientDSO, relies on the widely successful deep learning based approaches for visual saliency and scene parsing which drives the feature selection for obtaining highly-accurate and robust VO even in the presence of as few as 40 point features per frame. We provide extensive quantitative evaluation of SalientDSO on the ICL-NUIM and TUM monoVO datasets and show that we outperform DSO and ORB-SLAM - two very popular state-of-the-art approaches in the literature. We also collect and publicly release a CVL-UMD dataset which contains two indoor cluttered sequences on which we show qualitative evaluations. To our knowledge this is the first paper to use visual saliency and scene parsing to drive the feature selection in direct VO.

##### Abstract (translated by Google)
虽然混乱的室内场景有很多有用的高级语义信息可用于映射和定位，但大多数Visual Odometry（VO）算法依赖于几何特征（例如点，线和平面）的使用。最近，在这个想法的推动下，语义标签的联合优化和获取odometry已经在机器人界得到普及。联合优化对于准确的结果是有利的，但通常非常缓慢。与此同时，在视觉社区中，直接和稀疏的VO方法在速度和准确性之间取得了正确的平衡。
 我们合并了这两个社区的成功，并提出了一种将视觉显着形式的语义信息合并到Direct Sparse Odometry--一种非常成功的直接稀疏VO算法。我们还提出了一个基于场景分析来过滤视觉显着性的框架。我们的框架SalientDSO依赖于广泛成功的基于深度学习的视觉显着性和场景分析方法，即使在每帧只有40点特征的情况下，该方法也可以驱动特征选择以获得高度精确和强大的VO。我们对ICL-NUIM和TUM monoVO数据集上的SalientDSO提供了广泛的定量评估，并且表明我们超越了DSO和ORB-SLAM--这两种非常流行的文献中最先进的方法。我们还收集并公开发布CVL-UMD数据集，其中包含两个室内杂乱的序列，我们在其中显示定性评估结果。据我们所知，这是第一篇使用视觉显着性和场景分析来驱动直接VO中的特征选择的论文。

##### URL
[http://arxiv.org/abs/1803.00127](http://arxiv.org/abs/1803.00127)

##### PDF
[http://arxiv.org/pdf/1803.00127](http://arxiv.org/pdf/1803.00127)

