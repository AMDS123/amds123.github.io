---
layout: post
title: "BiSeNet: Bilateral Segmentation Network for Real-time Semantic Segmentation"
date: 2018-08-02 16:34:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Changqian Yu, Jingbo Wang, Chao Peng, Changxin Gao, Gang Yu, Nong Sang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation requires both rich spatial information and sizeable receptive field. However, modern approaches usually compromise spatial resolution to achieve real-time inference speed, which leads to poor performance. In this paper, we address this dilemma with a novel Bilateral Segmentation Network (BiSeNet). We first design a Spatial Path with a small stride to preserve the spatial information and generate high-resolution features. Meanwhile, a Context Path with a fast downsampling strategy is employed to obtain sufficient receptive field. On top of the two paths, we introduce a new Feature Fusion Module to combine features efficiently. The proposed architecture makes a right balance between the speed and segmentation performance on Cityscapes, CamVid, and COCO-Stuff datasets. Specifically, for a 2048x1024 input, we achieve 68.4% Mean IOU on the Cityscapes test dataset with speed of 105 FPS on one NVIDIA Titan XP card, which is significantly faster than the existing methods with comparable performance.

##### Abstract (translated by Google)
语义分割需要丰富的空间信息和相当大的感受野。但是，现代方法通常会牺牲空间分辨率来实现实时推理速度，从而导致性能不佳。在本文中，我们通过一种新颖的双边分割网络（BiSeNet）来解决这一难题。我们首先设计一个小步幅的空间路径，以保留空间信息并生成高分辨率特征。同时，采用具有快速下采样策略的上下文路径来获得足够的感知域。在这两条路径的顶部，我们引入了一个新的功能融合模块，以有效地结合功能。所提出的架构在Cityscapes，CamVid和COCO-Stuff数据集上的速度和分段性能之间取得了适当的平衡。具体来说，对于2048x1024输入，我们在Cityscapes测试数据集上实现了68.4％的平均IOU，在一块NVIDIA Titan XP卡上的速度为105 FPS，这明显快于具有可比性能的现有方法。

##### URL
[http://arxiv.org/abs/1808.00897](http://arxiv.org/abs/1808.00897)

##### PDF
[http://arxiv.org/pdf/1808.00897](http://arxiv.org/pdf/1808.00897)

