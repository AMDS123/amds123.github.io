---
layout: post
title: "Person Re-Identification by Camera Correlation Aware Feature Augmentation"
date: 2017-03-26 16:18:48
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Relation
author: Ying-Cong Chen, Xiatian Zhu, Wei-Shi Zheng, Jian-Huang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
The challenge of person re-identification (re-id) is to match individual images of the same person captured by different non-overlapping camera views against significant and unknown cross-view feature distortion. While a large number of distance metric/subspace learning models have been developed for re-id, the cross-view transformations they learned are view-generic and thus potentially less effective in quantifying the feature distortion inherent to each camera view. Learning view-specific feature transformations for re-id (i.e., view-specific re-id), an under-studied approach, becomes an alternative resort for this problem. In this work, we formulate a novel view-specific person re-identification framework from the feature augmentation point of view, called Camera coRrelation Aware Feature augmenTation (CRAFT). Specifically, CRAFT performs cross-view adaptation by automatically measuring camera correlation from cross-view visual data distribution and adaptively conducting feature augmentation to transform the original features into a new adaptive space. Through our augmentation framework, view-generic learning algorithms can be readily generalized to learn and optimize view-specific sub-models whilst simultaneously modelling view-generic discrimination information. Therefore, our framework not only inherits the strength of view-generic model learning but also provides an effective way to take into account view specific characteristics. Our CRAFT framework can be extended to jointly learn view-specific feature transformations for person re-id across a large network with more than two cameras, a largely under-investigated but realistic re-id setting. Additionally, we present a domain-generic deep person appearance representation which is designed particularly to be towards view invariant for facilitating cross-view adaptation by CRAFT.

##### Abstract (translated by Google)
人重新识别（re-id）的挑战是将由不同非重叠摄像机视图捕获的同一个人的个体图像与重要和未知的交叉视图特征失真匹配。虽然已经为re-id开发了大量的距离度量/子空间学习模型，但是他们所学习的交叉视图变换是通用的，因此在量化每个相机视图固有的特征失真方面可能不太有效。学习针对re-id的特定于视点的特征变换（即特定于视图的re-id）是一种研究不足的方法，成为此问题的替代手段。在这项工作中，我们从功能增强的角度，制定了一个新的视图特定的人重新识别框架，称为摄像机相关感知特征增强（CRAFT）。具体而言，CRAFT通过自动测量来自交叉视觉数据分布的相机相关性和自适应地执行特征增强以将原始特征转换为新的自适应空间来执行交叉视图适应。通过我们的增强框架，查看泛型学习算法可以很容易地推广到学习和优化特定于视点的子模型，同时建模视图泛型区分信息。因此，我们的框架不仅继承了视图 - 通用模型学习的优势，而且提供了考虑视图特定特征的有效方法。我们的CRAFT框架可以扩展到联合学习特定视角的特征转换，用于在具有两个以上摄像机的大型网络上进行个人身份识别，这是一个很大程度上被低估但是逼真的re-id设置。此外，我们提出了一个领域通用的深度人物外观表示，这是特别设计，以促进交叉视图适应由CRAFT视图不变。

##### URL
[https://arxiv.org/abs/1703.08837](https://arxiv.org/abs/1703.08837)

##### PDF
[https://arxiv.org/pdf/1703.08837](https://arxiv.org/pdf/1703.08837)

