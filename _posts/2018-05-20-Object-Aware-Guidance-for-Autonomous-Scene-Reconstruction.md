---
layout: post
title: "Object-Aware Guidance for Autonomous Scene Reconstruction"
date: 2018-05-20 16:44:20
categories: arXiv_RO
tags: arXiv_RO Segmentation Face
author: Ligang Liu, Xi Xia, Han Sun, Qi Shen, Juzhan Xu, Bin Chen, Hui Huang, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
To carry out autonomous 3D scanning and online reconstruction of unknown indoor scenes, one has to find a balance between global exploration of the entire scene and local scanning of the objects within it. In this work, we propose a novel approach, which provides object-aware guidance for autoscanning, for exploring, reconstructing, and understanding an unknown scene within one navigation pass. Our approach interleaves between object analysis to identify the next best object (NBO) for global exploration, and object-aware information gain analysis to plan the next best view (NBV) for local scanning. First, an objectness-based segmentation method is introduced to extract semantic objects from the current scene surface via a multi-class graph cuts minimization. Then, an object of interest (OOI) is identified as the NBO which the robot aims to visit and scan. The robot then conducts fine scanning on the OOI with views determined by the NBV strategy. When the OOI is recognized as a full object, it can be replaced by its most similar 3D model in a shape database. The algorithm iterates until all of the objects are recognized and reconstructed in the scene. Various experiments and comparisons have shown the feasibility of our proposed approach.

##### Abstract (translated by Google)
为了对未知的室内场景进行自主3D扫描和在线重建，必须在整个场景的全局探索和其内部对象的局部扫描之间找到平衡。在这项工作中，我们提出了一种新方法，它为自动扫描提供了对象感知指导，用于在一个导航过程中探索，重建和理解未知场景。我们的方法在对象分析之间交错，以识别用于全局探索的下一个最佳对象（NBO），以及用于计划用于本地扫描的下一个最佳视图（NBV）的对象感知信息增益分析。首先，引入基于对象性的分割方法，以通过多类图切割最小化从当前场景表面提取语义对象。然后，感兴趣的对象（OOI）被识别为机器人旨在访问和扫描的NBO。然后机器人在OOI上进行精细扫描，其视图由NBV策略确定。当OOI被识别为完整对象时，它可以被形状数据库中最相似的3D模型替换。该算法迭代，直到在场景中识别和重建所有对象。各种实验和比较表明了我们提出的方法的可行性。

##### URL
[http://arxiv.org/abs/1805.07794](http://arxiv.org/abs/1805.07794)

##### PDF
[http://arxiv.org/pdf/1805.07794](http://arxiv.org/pdf/1805.07794)

