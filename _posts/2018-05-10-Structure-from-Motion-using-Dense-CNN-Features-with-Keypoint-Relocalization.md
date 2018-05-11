---
layout: post
title: "Structure-from-Motion using Dense CNN Features with Keypoint Relocalization"
date: 2018-05-10 08:35:06
categories: arXiv_CV
tags: arXiv_CV CNN
author: Aji Resindra W, Akihiko Torii, Masatoshi Okutomi
mathjax: true
---

* content
{:toc}

##### Abstract
Structure from Motion (SfM) using imagery that involves extreme appearance changes is yet a challenging task due to a loss of feature repeatability. Using feature correspondences obtained by matching densely extracted convolutional neural network (CNN) features significantly improves the SfM reconstruction capability. However, the reconstruction accuracy is limited by the spatial resolution of the extracted CNN features which is not even pixel-level accuracy in the existing approach. Providing dense feature matches with precise keypoint positions is not trivial because of memory limitation and computational burden of dense features. To achieve accurate SfM reconstruction with highly repeatable dense features, we propose an SfM pipeline that uses dense CNN features with relocalization of keypoint position that can efficiently and accurately provide pixel-level feature correspondences. Then, we demonstrate on the Aachen Day-Night dataset that the proposed SfM using dense CNN features with the keypoint relocalization outperforms a state-of-the-art SfM (COLMAP using RootSIFT) by a large margin.

##### Abstract (translated by Google)
运动结构（SfM）使用涉及极端外观变化的图像，但由于功能可重复性的损失，这仍然是一项具有挑战性的任务。通过匹配密集提取的卷积神经网络（CNN）特征获得的特征对应性显着提高了SfM重建能力。然而，重建准确度受到提取的CNN特征的空间分辨率的限制，这在现有方法中甚至不是像素级准确度。由于密集特征的内存限制和计算负担，提供与精确关键点位置密集的特征匹配并不是微不足道的。为了实现具有高度可重复密集特征的精确SfM重建，我们提出了一种SfM流水线，该流水线使用密集的CNN特征和关键点位置的重新定位，可以高效准确地提供像素级特征对应。然后，我们在亚琛日 - 夜数据集上演示，使用密集CNN特征的关键点重定位所提出的SfM优于最先进的SfM（使用RootSIFT的COLMAP）。

##### URL
[http://arxiv.org/abs/1805.03879](http://arxiv.org/abs/1805.03879)

##### PDF
[http://arxiv.org/pdf/1805.03879](http://arxiv.org/pdf/1805.03879)

