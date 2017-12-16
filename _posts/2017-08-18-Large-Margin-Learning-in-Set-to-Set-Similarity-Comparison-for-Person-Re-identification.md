---
layout: post
title: "Large Margin Learning in Set to Set Similarity Comparison for Person Re-identification"
date: 2017-08-18 05:19:01
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Person_Re-identification CNN Deep_Learning
author: Sanping Zhou, Jinjun Wang, Rui Shi, Qiqi Hou, Yihong Gong, Nanning Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) aims at matching images of the same person across disjoint camera views, which is a challenging problem in multimedia analysis, multimedia editing and content-based media retrieval communities. The major challenge lies in how to preserve similarity of the same person across video footages with large appearance variations, while discriminating different individuals. To address this problem, conventional methods usually consider the pairwise similarity between persons by only measuring the point to point (P2P) distance. In this paper, we propose to use deep learning technique to model a novel set to set (S2S) distance, in which the underline objective focuses on preserving the compactness of intra-class samples for each camera view, while maximizing the margin between the intra-class set and inter-class set. The S2S distance metric is consisted of three terms, namely the class-identity term, the relative distance term and the regularization term. The class-identity term keeps the intra-class samples within each camera view gathering together, the relative distance term maximizes the distance between the intra-class class set and inter-class set across different camera views, and the regularization term smoothness the parameters of deep convolutional neural network (CNN). As a result, the final learned deep model can effectively find out the matched target to the probe object among various candidates in the video gallery by learning discriminative and stable feature representations. Using the CUHK01, CUHK03, PRID2011 and Market1501 benchmark datasets, we extensively conducted comparative evaluations to demonstrate the advantages of our method over the state-of-the-art approaches.

##### Abstract (translated by Google)
个人重新识别（Re-ID）旨在通过不相交的相机视图匹配同一个人的图像，这在多媒体分析，多媒体编辑和基于内容的媒体检索社区中是一个具有挑战性的问题。主要的挑战在于如何保持同一个人在不同视频片段之间具有较大外观变化的相似性，同时区分不同的个体。为了解决这个问题，传统方法通常只考虑点到点（P2P）距离来考虑人与人之间的配对相似度。在本文中，我们建议使用深度学习技术来建立一个新的集（S2S）距离，其中下划线的目标集中在保持每个摄像机视图的类内样本的紧凑性，同时最大化帧间班级集和班级集。 S2S距离度量由三个项组成，即类一致性项，相对距离项和正则化项。类别同一性术语使得每个相机视图内的类内样本聚集在一起，相对距离项最大化不同类别摄像机视图内的类内类别集合和类间集合之间的距离，并且正则化术语平滑参数深卷积神经网络（CNN）。因此，最终的学习深度模型可以通过学习判别性和稳定的特征表示，有效地找出视频库中各候选对象与探测对象的匹配目标。使用CUHK01，CUHK03，PRID2011和Market1501基准数据集，我们进行了广泛的比较评估，以证明我们的方法相对于最先进的方法的优势。

##### URL
[https://arxiv.org/abs/1708.05512](https://arxiv.org/abs/1708.05512)

##### PDF
[https://arxiv.org/pdf/1708.05512](https://arxiv.org/pdf/1708.05512)

