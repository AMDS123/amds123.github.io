---
layout: post
title: "Improving Object Detection from Scratch via Gated Feature Reuse"
date: 2019-07-07 16:37:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Zhiqiang Shen, Honghui Shi, Jiahui Yu, Hai Phan, Rogerio Feris, Liangliang Cao, Ding Liu, Xinchao Wang, Thomas Huang, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a simple and parameter-efficient drop-in module for one-stage object detectors like SSD when learning from scratch (i.e., without pre-trained models). We call our module GFR (Gated Feature Reuse), which exhibits two main advantages. First, we introduce a novel gate-controlled prediction strategy enabled by Squeeze-and-Excitation to adaptively enhance or attenuate supervision at different scales based on the input object size. As a result, our model is more effective in detecting diverse sizes of objects. Second, we propose a feature-pyramids structure to squeeze rich spatial and semantic features into a single prediction layer, which strengthens feature representation and reduces the number of parameters to learn. We apply the proposed structure on DSOD and SSD detection frameworks, and evaluate the performance on PASCAL VOC 2007, 2012 and COCO datasets. With fewer model parameters, GFR-DSOD outperforms the baseline DSOD by 1.4%, 1.1%, 1.7% and 0.6%, respectively. GFR-SSD also outperforms the original SSD and SSD with dense prediction by 3.6% and 2.8% on VOC 2007 dataset. Code is available at: https://github.com/szq0214/GFR-DSOD .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.00886](http://arxiv.org/abs/1712.00886)

##### PDF
[http://arxiv.org/pdf/1712.00886](http://arxiv.org/pdf/1712.00886)

