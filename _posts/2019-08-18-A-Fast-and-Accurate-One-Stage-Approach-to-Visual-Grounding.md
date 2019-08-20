---
layout: post
title: "A Fast and Accurate One-Stage Approach to Visual Grounding"
date: 2019-08-18 00:25:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding Optimization Detection
author: Zhengyuan Yang, Boqing Gong, Liwei Wang, Wenbing Huang, Dong Yu, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple, fast, and accurate one-stage approach to visual grounding, inspired by the following insight. The performances of existing propose-and-rank two-stage methods are capped by the quality of the region candidates they propose in the first stage --- if none of the candidates could cover the ground truth region, there is no hope in the second stage to rank the right region to the top. To avoid this caveat, we propose a one-stage model that enables end-to-end joint optimization. The main idea is as straightforward as fusing a text query's embedding into the YOLOv3 object detector, augmented by spatial features so as to account for spatial mentions in the query. Despite being simple, this one-stage approach shows great potential in terms of both accuracy and speed for both phrase localization and referring expression comprehension, according to our experiments. Given these results along with careful investigations into some popular region proposals, we advocate for visual grounding a paradigm shift from the conventional two-stage methods to the one-stage framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06354](http://arxiv.org/abs/1908.06354)

##### PDF
[http://arxiv.org/pdf/1908.06354](http://arxiv.org/pdf/1908.06354)

