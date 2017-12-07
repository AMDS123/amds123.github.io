---
layout: post
title: "Learning Hough Regression Models via Bridge Partial Least Squares for Object Detection"
date: 2016-03-26 09:33:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jianyu Tang, Hanzi Wang, Yan Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Popular Hough Transform-based object detection approaches usually construct an appearance codebook by clustering local image features. However, how to choose appropriate values for the parameters used in the clustering step remains an open problem. Moreover, some popular histogram features extracted from overlapping image blocks may cause a high degree of redundancy and multicollinearity. In this paper, we propose a novel Hough Transform-based object detection approach. First, to address the above issues, we exploit a Bridge Partial Least Squares (BPLS) technique to establish context-encoded Hough Regression Models (HRMs), which are linear regression models that cast probabilistic Hough votes to predict object locations. BPLS is an efficient variant of Partial Least Squares (PLS). PLS-based regression techniques (including BPLS) can reduce the redundancy and eliminate the multicollinearity of a feature set. And the appropriate value of the only parameter used in PLS (i.e., the number of latent components) can be determined by using a cross-validation procedure. Second, to efficiently handle object scale changes, we propose a novel multi-scale voting scheme. In this scheme, multiple Hough images corresponding to multiple object scales can be obtained simultaneously. Third, an object in a test image may correspond to multiple true and false positive hypotheses at different scales. Based on the proposed multi-scale voting scheme, a principled strategy is proposed to fuse hypotheses to reduce false positives by evaluating normalized pointwise mutual information between hypotheses. In the experiments, we also compare the proposed HRM approach with its several variants to evaluate the influences of its components on its performance. Experimental results show that the proposed HRM approach has achieved desirable performances on popular benchmark datasets.

##### Abstract (translated by Google)
流行的基于Hough变换的对象检测方法通常通过对局部图像特征进行聚类来构造外观代码簿。但是，如何为聚类步骤中使用的参数选择适当的值仍然是一个悬而未决的问题。而且，从重叠图像块中提取的一些流行的直方图特征可能导致高度冗余和多重共线性。在本文中，我们提出了一种新颖的基于Hough变换的物体检测方法。首先，为了解决上述问题，我们利用桥部分最小二乘（BPLS）技术来建立上下文编码的霍夫回归模型（HRM），这是一种线性回归模型，用于投射概率霍夫投票来预测目标位置。 BPLS是偏最小二乘（PLS）的有效变体。基于PLS的回归技术（包括BPLS）可以减少冗余，消除特征集的多重共线性。并且可以通过使用交叉验证程序来确定在PLS中使用的唯一参数的适当值（即，潜在分量的数目）。其次，为了有效地处理对象尺度变化，我们提出了一种新的多尺度投票方案。在这个方案中，可以同时获得与多个对象尺度相对应的多个霍夫图像。第三，测试图像中的对象可能对应于不同尺度下的多个真假假设。在提出的多尺度投票方案的基础上，提出了一种原则性的策略，通过评估假设之间的归一化的逐点互信息来融合假设来减少误报。在实验中，我们还将所提出的HRM方法与其几个变体进行比较，以评估其组件对其性能的影响。实验结果表明，提出的人力资源管理方法已经在流行的基准数据集上取得了理想的表现

##### URL
[https://arxiv.org/abs/1603.08092](https://arxiv.org/abs/1603.08092)

##### PDF
[https://arxiv.org/pdf/1603.08092](https://arxiv.org/pdf/1603.08092)

