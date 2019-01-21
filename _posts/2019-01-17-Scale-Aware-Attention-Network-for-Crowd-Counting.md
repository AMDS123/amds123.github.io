---
layout: post
title: "Scale-Aware Attention Network for Crowd Counting"
date: 2019-01-17 22:50:56
categories: arXiv_CV
tags: arXiv_CV Attention CNN Prediction
author: Rahul Rama Varior, Bing Shuai, Joe Tighe, Davide Modolo
mathjax: true
---

* content
{:toc}

##### Abstract
In crowd counting datasets, people appear at different scales, depending on their distance to the camera. To address this issue, we propose a novel multi-branch scale-aware attention network that exploits the hierarchical structure of convolutional neural networks and generates, in a single forward pass, multi-scale density predictions from different layers of the architecture. To aggregate these maps into our final prediction, we present a new soft attention mechanism that learns a set of gating masks. Furthermore, we introduce a scale-aware loss function to regularize the training of different branches and guide them to specialize on a particular scale. As this new training requires ground-truth annotations for the size of each head, we also propose a simple, yet effective technique to estimate it automatically. Finally, we present an ablation study on each of these components and compare our approach against the literature on 4 crowd counting datasets: UCF-QNRF, ShanghaiTech A &amp; B and UCF_CC_50. Without bells and whistles, our approach achieves state-of-the-art on all these datasets. We observe a remarkable improvement on the UCF-QNRF (25%) and a significant one on the others (around 10%).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06026](http://arxiv.org/abs/1901.06026)

##### PDF
[http://arxiv.org/pdf/1901.06026](http://arxiv.org/pdf/1901.06026)

