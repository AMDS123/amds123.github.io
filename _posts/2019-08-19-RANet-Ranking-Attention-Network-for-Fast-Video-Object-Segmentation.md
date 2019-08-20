---
layout: post
title: "RANet: Ranking Attention Network for Fast Video Object Segmentation"
date: 2019-08-19 08:58:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Ziqin Wang, Jun Xu, Li Liu, Fan Zhu, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Despite online learning (OL) techniques have boosted the performance of semi-supervised video object segmentation (VOS) methods, the huge time costs of OL greatly restricts their practicality. Matching based and propagation based methods run at a faster speed by avoiding OL techniques. However, they are limited by sub-optimal accuracy, due to mismatching and drifting problems. In this paper, we develop a real-time yet very accurate Ranking Attention Network (RANet) for VOS. Specifically, to integrate the insights of matching based and propagation based methods, we employ an encoder-decoder framework to learn pixel-level similarity and segmentation in an end-to-end manner. To better utilize the similarity maps, we propose a novel ranking attention module, which automatically ranks and selects these maps for fine-grained VOS performance. Experiments on DAVIS_16 and DAVIS_17 datasets show that our RANet achieves the best speed-accuracy trade-off, e.g., with 33 milliseconds per frame and J&amp;F=85.5% on DAVIS_16. With OL, our RANet reaches J&amp;F=87.1% on DAVIS_16, exceeding state-of-the-art VOS methods. The code can be found at https://github.com/Storife/RANet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06647](http://arxiv.org/abs/1908.06647)

##### PDF
[http://arxiv.org/pdf/1908.06647](http://arxiv.org/pdf/1908.06647)

