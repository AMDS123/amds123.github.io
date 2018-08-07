---
layout: post
title: "Learning monocular depth estimation with unsupervised trinocular assumptions"
date: 2018-08-05 12:33:06
categories: arXiv_CV
tags: arXiv_CV
author: Matteo Poggi, Fabio Tosi, Stefano Mattoccia
mathjax: true
---

* content
{:toc}

##### Abstract
Obtaining accurate depth measurements out of a single image represents a fascinating solution to 3D sensing. CNNs led to considerable improvements in this field, and recent trends replaced the need for ground-truth labels with geometry-guided image reconstruction signals enabling unsupervised training. Currently, for this purpose, state-of-the-art techniques rely on images acquired with a binocular stereo rig to predict inverse depth (i.e., disparity) according to the aforementioned supervision principle. However, these methods suffer from well-known problems near occlusions, left image border, etc inherited from the stereo setup. Therefore, in this paper, we tackle these issues by moving to a trinocular domain for training. Assuming the central image as the reference, we train a CNN to infer disparity representations pairing such image with frames on its left and right side. This strategy allows obtaining depth maps not affected by typical stereo artifacts. Moreover, being trinocular datasets seldom available, we introduce a novel interleaved training procedure enabling to enforce the trinocular assumption outlined from current binocular datasets. Exhaustive experimental results on the KITTI dataset confirm that our proposal outperforms state-of-the-art methods for unsupervised monocular depth estimation trained on binocular stereo pairs as well as any known methods relying on other cues.

##### Abstract (translated by Google)
从单个图像中获取精确的深度测量值代表了3D感测的迷人解决方案。 CNN在这一领域取得了相当大的进步，最近的趋势取代了对地面实况标签的需求，这些标签具有几何引导的图像重建信号，可实现无监督训练。目前，为此目的，现有技术依赖于利用双目立体装置获取的图像来根据前述监督原理来预测逆深度（即，视差）。然而，这些方法在从立体声设置继承的遮挡，左图像边界等附近遭受众所周知的问题。因此，在本文中，我们通过转向三目域进行培训来解决这些问题。假设中心图像作为参考，我们训练CNN以推断将这种图像与其左侧和右侧的帧配对的视差表示。该策略允许获得不受典型立体声伪影影响的深度图。此外，作为三目数据集很少可用，我们引入了一种新颖的交错训练程序，能够强制执行当前双目数据集概述的三目假设。 KITTI数据集上的详尽实验结果证实，我们的提议优于最先进的方法，用于在双目立体对上训练的无监督单眼深度估计以及依赖于其他线索的任何已知方法。

##### URL
[https://arxiv.org/abs/1808.01606](https://arxiv.org/abs/1808.01606)

##### PDF
[https://arxiv.org/pdf/1808.01606](https://arxiv.org/pdf/1808.01606)

