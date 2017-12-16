---
layout: post
title: "SceneCut: Joint Geometric and Object Segmentation for Indoor Scenes"
date: 2017-09-21 05:08:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Deep_Learning
author: Trung Pham, Thanh-Toan Do, Niko Sünderhauf, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents SceneCut, a novel approach to jointly discover previously unseen objects and non-object surfaces using a single RGB-D image. SceneCut's joint reasoning over scene semantics and geometry allows a robot to detect and segment object instances in complex scenes where modern deep learning-based methods either fail to separate object instances, or fail to detect objects that were not seen during training. SceneCut automatically decomposes a scene into meaningful regions which either represent objects or scene surfaces. The decomposition is qualified by an unified energy function over objectness and geometric fitting. We show how this energy function can be optimized efficiently by utilizing hierarchical segmentation trees. Moreover, we leverage a pre-trained convolutional oriented boundary network to predict accurate boundaries from images, which are used to construct high-quality region hierarchies. We evaluate SceneCut on several different indoor environments, and the results show that SceneCut significantly outperforms all the existing methods.

##### Abstract (translated by Google)
本文介绍了SceneCut，一种使用单个RGB-D图像联合发现以前看不见的物体和非物体表面的新方法。 SceneCut对场景语义和几何的联合推理允许机器人检测和分割复杂场景中的对象实例，其中现代的基于深度学习的方法无法分离对象实例，或者未能检测到在训练期间看不到的对象。 SceneCut会自动将场景分解为表示对象或场景表面的有意义的区域。分解是通过一个统一的能量函数而不是对象和几何拟合来确定的。我们展示了如何利用层次分割树来有效地优化这个能量函数。此外，我们利用预先训练的卷积导向边界网络来预测图像的准确边界，这些边界用于构建高质量的区域分层结构。我们在几个不同的室内环境中评估SceneCut，结果显示SceneCut明显优于所有现有的方法。

##### URL
[https://arxiv.org/abs/1709.07158](https://arxiv.org/abs/1709.07158)

##### PDF
[https://arxiv.org/pdf/1709.07158](https://arxiv.org/pdf/1709.07158)

