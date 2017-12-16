---
layout: post
title: "Feature Sensitive Label Fusion with Random Walker for Atlas-based Image Segmentation"
date: 2017-11-09 15:13:11
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation
author: Siqi Bao, Albert C. S. Chung
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a novel label fusion method is proposed for brain magnetic resonance image segmentation. This label fusion method is formulated on a graph, which embraces both label priors from atlases and anatomical priors from target image. To represent a pixel in a comprehensive way, three kinds of feature vectors are generated, including intensity, gradient and structural signature. To select candidate atlas nodes for fusion, rather than exact searching, randomized k-d tree with spatial constraint is introduced as an efficient approximation for high-dimensional feature matching. Feature Sensitive Label Prior (FSLP), which takes both the consistency and variety of different features into consideration, is proposed to gather atlas priors. As FSLP is a non-convex problem, one heuristic approach is further designed to solve it efficiently. Moreover, based on the anatomical knowledge, parts of the target pixels are also employed as graph seeds to assist the label fusion process and an iterative strategy is utilized to gradually update the label map. The comprehensive experiments carried out on two publicly available databases give results to demonstrate that the proposed method can obtain better segmentation quality.

##### Abstract (translated by Google)
本文提出了一种新的标记融合方法用于脑部磁共振图像分割。这个标签融合方法是在一个图形上制定的，它包含了来自地图的标签先验图像和目标图像的解剖先验图像。为了综合表示像素，生成三种特征向量，包括强度，梯度和结构特征。为了选择候选图集节点进行融合，而不是精确搜索，引入具有空间约束的随机k-d树作为高维特征匹配的高效逼近。提出特征敏感标签优先（Feature Sensitive Label Prior，FSLP）方法来考虑不同特征的一致性和多样性，以收集图谱的先验知识。由于FSLP是一个非凸问题，因此进一步设计一种启发式方法来有效地解决这个问题。此外，基于解剖学知识，目标像素的部分也被用作图种子来协助标签融合过程，并且利用迭代策略逐渐更新标签图。在两个公开的数据库上进行的综合实验结果表明，所提出的方法可以获得更好的分割质量。

##### URL
[https://arxiv.org/abs/1610.07475](https://arxiv.org/abs/1610.07475)

##### PDF
[https://arxiv.org/pdf/1610.07475](https://arxiv.org/pdf/1610.07475)

