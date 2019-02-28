---
layout: post
title: "Recurrent MVSNet for High-resolution Multi-view Stereo Depth Inference"
date: 2019-02-27 14:34:50
categories: arXiv_CV
tags: arXiv_CV Regularization Inference Deep_Learning
author: Yao Yao, Zixin Luo, Shiwei Li, Tianwei Shen, Tian Fang, Long Quan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has recently demonstrated its excellent performance for multi-view stereo (MVS). However, one major limitation of current learned MVS approaches is the scalability: the memory-consuming cost volume regularization makes the learned MVS hard to be applied to high-resolution scenes. In this paper, we introduce a scalable multi-view stereo framework based on the recurrent neural network. Instead of regularizing the entire 3D cost volume in one go, the proposed Recurrent Multi-view Stereo Network (R-MVSNet) sequentially regularizes the 2D cost maps along the depth direction via the gated recurrent unit (GRU). This reduces dramatically the memory consumption and makes high-resolution reconstruction feasible. We first show the state-of-the-art performance achieved by the proposed R-MVSNet on the recent MVS benchmarks. Then, we further demonstrate the scalability of the proposed method on several large-scale scenarios, where previous learned approaches often fail due to the memory constraint. Code is available at https://github.com/YoYo000/MVSNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10556](http://arxiv.org/abs/1902.10556)

##### PDF
[http://arxiv.org/pdf/1902.10556](http://arxiv.org/pdf/1902.10556)

