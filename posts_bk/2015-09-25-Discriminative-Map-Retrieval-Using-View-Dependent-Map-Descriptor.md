---
layout: post
title: "Discriminative Map Retrieval Using View-Dependent Map Descriptor"
date: 2015-09-25 08:02:19
categories: arXiv_CV
tags: arXiv_CV Detection
author: Enfu Liu, Kanji Tanaka
mathjax: true
---

* content
{:toc}

##### Abstract
Map retrieval, the problem of similarity search over a large collection of 2D pointset maps previously built by mobile robots, is crucial for autonomous navigation in indoor and outdoor environments. Bag-of-words (BoW) methods constitute a popular approach to map retrieval; however, these methods have extremely limited descriptive ability because they ignore the spatial layout information of the local features. The main contribution of this paper is an extension of the bag-of-words map retrieval method to enable the use of spatial information from local features. Our strategy is to explicitly model a unique viewpoint of an input local map; the pose of the local feature is defined with respect to this unique viewpoint, and can be viewed as an additional invariant feature for discriminative map retrieval. Specifically, we wish to determine a unique viewpoint that is invariant to moving objects, clutter, occlusions, and actual viewpoints. Hence, we perform scene parsing to analyze the scene structure, and consider the "center" of the scene structure to be the unique viewpoint. Our scene parsing is based on a Manhattan world grammar that imposes a quasi-Manhattan world constraint to enable the robust detection of a scene structure that is invariant to clutter and moving objects. Experimental results using the publicly available radish dataset validate the efficacy of the proposed approach.

##### Abstract (translated by Google)
地图检索是以前由移动机器人构建的大量2D点集地图的相似搜索问题，对于室内和室外环境中的自主导航至关重要。单词袋（BoW）方法构成地图检索的常用方法;然而，这些方法由于忽略了局部特征的空间布局信息而具有非常有限的描述能力。本文的主要贡献是扩展了字符映射检索方法，使得能够使用来自局部特征的空间信息。我们的策略是明确地建模一个输入本地地图的独特视角;局部特征的姿态相对于这个独特的视点被定义，并且可以被视为用于区分性地图检索的附加不变特征。具体而言，我们希望确定一个独特的观点，这个观点对于运动物体，杂波，遮挡物和实际观点是不变的。因此，我们进行场景解析来分析场景结构，并将场景结构的“中心”视为独特的视点。我们的场景分析是基于曼哈顿的世界语法，强制准曼哈顿的世界约束，使强大的检测场景结构是不变的混乱和移动的对象。使用公开可用的萝卜数据集的实验结果证实了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1509.07615](https://arxiv.org/abs/1509.07615)

##### PDF
[https://arxiv.org/pdf/1509.07615](https://arxiv.org/pdf/1509.07615)

