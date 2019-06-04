---
layout: post
title: "Detecting Multi-Oriented Text with Corner-based Region Proposals"
date: 2019-06-03 00:50:50
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Detection
author: Linjie Deng, Yanxiang Gong, Yi Lin, Jingwen Shuai, Xiaoguang Tu, Yuefei Zhang, Zheng Ma, Mei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Previous approaches for scene text detection usually rely on manually defined sliding windows. This work presents an intuitive two-stage region-based method to detect multi-oriented text without any prior knowledge regarding the textual shape. In the first stage, we estimate the possible locations of text instances by detecting and linking corners instead of shifting a set of default anchors. The quadrilateral proposals are geometry adaptive, which allows our method to cope with various text aspect ratios and orientations. In the second stage, we design a new pooling layer named Dual-RoI Pooling which embeds data augmentation inside the region-wise subnetwork for more robust classification and regression over these proposals. Experimental results on public benchmarks confirm that the proposed method is capable of achieving comparable performance with state-of-the-art methods. The code is publicly available at https://github.com/xhzdeng/crpn

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.02690](http://arxiv.org/abs/1804.02690)

##### PDF
[http://arxiv.org/pdf/1804.02690](http://arxiv.org/pdf/1804.02690)

