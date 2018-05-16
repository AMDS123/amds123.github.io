---
layout: post
title: "Robust Facial Landmark Localization Based on Texture and Pose Correlated Initialization"
date: 2018-05-15 07:51:45
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Detection Relation
author: Yiyun Pan, Junwei Zhou, Yongsheng Gao, Shengwu Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Robust facial landmark localization remains a challenging task when faces are partially occluded. Recently, the cascaded pose regression has attracted increasing attentions, due to it's superior performance in facial landmark localization and occlusion detection. However, such an approach is sensitive to initialization, where an improper initialization can severly degrade the performance. In this paper, we propose a Robust Initialization for Cascaded Pose Regression (RICPR) by providing texture and pose correlated initial shapes for the testing face. By examining the correlation of local binary patterns histograms between the testing face and the training faces, the shapes of the training faces that are most correlated with the testing face are selected as the texture correlated initialization. To make the initialization more robust to various poses, we estimate the rough pose of the testing face according to five fiducial landmarks located by multitask cascaded convolutional networks. Then the pose correlated initial shapes are constructed by the mean face's shape and the rough testing face pose. Finally, the texture correlated and the pose correlated initial shapes are joined together as the robust initialization. We evaluate RICPR on the challenging dataset of COFW. The experimental results demonstrate that the proposed scheme achieves better performances than the state-of-the-art methods in facial landmark localization and occlusion detection.

##### Abstract (translated by Google)
面部部分遮挡时，强健的面部标志性定位仍然是一项具有挑战性的任务。最近，级联姿态回归已经引起越来越多的关注，因为它在面部地标定位和遮挡检测方面表现出色。但是，这种方法对初始化很敏感，因为不恰当的初始化会严重降低性能。在本文中，我们通过为测试面提供纹理和姿态相关的初始形状，提出了级联姿态回归（RICPR）的稳健初始化。通过检查测试人脸和训练人脸之间的局部二值模式直方图的相关性，选择与测试人脸最相关的训练人脸的形状作为纹理相关初始化。为了使初始化对各种姿态更加稳健，我们根据多任务级联卷积网络定位的五个基准点标记来估计测试面的粗略姿态。然后，通过平均脸部的形状和粗糙的测试脸部姿态来构造相关的初始形状。最后，相关的纹理和姿态相关的初始形状被连接在一起作为稳健的初始化。我们在COFW的具有挑战性的数据集上评估RICPR。实验结果表明，所提出的方案在面部地标定位和遮挡检测中比现有技术方法具有更好的性能。

##### URL
[http://arxiv.org/abs/1805.05612](http://arxiv.org/abs/1805.05612)

##### PDF
[http://arxiv.org/pdf/1805.05612](http://arxiv.org/pdf/1805.05612)

