---
layout: post
title: "Effective Use of Dilated Convolutions for Segmenting Small Object Instances in Remote Sensing Imagery"
date: 2017-09-01 07:20:01
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Ryuhei Hamaguchi, Aito Fujita, Keisuke Nemoto, Tomoyuki Imaizumi, Shuhei Hikosaka
mathjax: true
---

* content
{:toc}

##### Abstract
Thanks to recent advances in CNNs, solid improvements have been made in semantic segmentation of high resolution remote sensing imagery. However, most of the previous works have not fully taken into account the specific difficulties that exist in remote sensing tasks. One of such difficulties is that objects are small and crowded in remote sensing imagery. To tackle with this challenging task we have proposed a novel architecture called local feature extraction (LFE) module attached on top of dilated front-end module. The LFE module is based on our findings that aggressively increasing dilation factors fails to aggregate local features due to sparsity of the kernel, and detrimental to small objects. The proposed LFE module solves this problem by aggregating local features with decreasing dilation factor. We tested our network on three remote sensing datasets and acquired remarkably good results for all datasets especially for small objects.

##### Abstract (translated by Google)
由于CNN的最新进展，高分辨率遥感影像的语义分割已经取得了很大的进展。但是，以往的大部分工作还没有充分考虑到遥感任务存在的具体困难。其中一个难题就是遥感影像中的物体小而拥挤。为了解决这个具有挑战性的任务，我们已经提出了一种称为局部特征提取（LFE）模块的新颖架构，该模块连接在扩张的前端模块上。 LFE模块是基于我们的发现，积极增加膨胀因子不能聚集局部特征，这是由于内核的稀疏性以及对小物体的不利影响。所提出的LFE模块通过聚集局部特征和减小的膨胀因子来解决这个问题。我们在三个遥感数据集上测试了我们的网络，并获得了所有数据集，尤其是小型物体的显着好结果。

##### URL
[https://arxiv.org/abs/1709.00179](https://arxiv.org/abs/1709.00179)

##### PDF
[https://arxiv.org/pdf/1709.00179](https://arxiv.org/pdf/1709.00179)

