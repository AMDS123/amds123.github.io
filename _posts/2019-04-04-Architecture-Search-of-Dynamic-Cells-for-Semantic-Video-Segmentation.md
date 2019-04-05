---
layout: post
title: "Architecture Search of Dynamic Cells for Semantic Video Segmentation"
date: 2019-04-04 06:32:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Vladimir Nekrasov, Hao Chen, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In semantic video segmentation the goal is to acquire consistent dense semantic labelling across image frames. To this end, recent approaches have been reliant on manually arranged operations applied on top of static semantic segmentation networks - with the most prominent building block being the optical flow able to provide information about scene dynamics. Related to that is the line of research concerned with speeding up static networks by approximating expensive parts of them with cheaper alternatives, while propagating information from previous frames. In this work we attempt to come up with generalisation of those methods, and instead of manually designing contextual blocks that connect per-frame outputs, we propose a neural architecture search solution, where the choice of operations together with their sequential arrangement are being predicted by a separate neural network. We showcase that such generalisation leads to stable and accurate results across common benchmarks, such as CityScapes and CamVid datasets. Importantly, the proposed methodology takes only 2 GPU-days, finds high-performing cells and does not rely on the expensive optical flow computation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02371](http://arxiv.org/abs/1904.02371)

##### PDF
[http://arxiv.org/pdf/1904.02371](http://arxiv.org/pdf/1904.02371)

