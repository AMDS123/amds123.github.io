---
layout: post
title: "Real-Time Correlation Tracking via Joint Model Compression and Transfer"
date: 2019-07-23 11:57:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Tracking Image_Classification Classification Relation Recognition
author: Ning Wang, Wengang Zhou, Yibing Song, Chao Ma, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Correlation filters (CF) have received considerable attention in visual tracking because of their computational efficiency. Leveraging deep features via off-the-shelf CNN models (e.g., VGG), CF trackers achieve state-of-the-art performance while consuming a large number of computing resources. This limits deep CF trackers to be deployed to many mobile platforms on which only a single-core CPU is available. In this paper, we propose to jointly compress and transfer off-the-shelf CNN models within a knowledge distillation framework. We formulate a CNN model pretrained from the image classification task as a teacher network, and distill this teacher network into a lightweight student network as the feature extractor to speed up CF trackers. In the distillation process, we propose a fidelity loss to enable the student network to maintain the representation capability of the teacher network. Meanwhile, we design a tracking loss to adapt the objective of the student network from object recognition to visual tracking. The distillation process is performed offline on multiple layers and adaptively updates the student network using a background-aware online learning scheme. Extensive experiments on five challenging datasets demonstrate that the lightweight student network accelerates the speed of state-of-the-art deep CF trackers to real-time on a single-core CPU while maintaining almost the same tracking accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09831](http://arxiv.org/abs/1907.09831)

##### PDF
[http://arxiv.org/pdf/1907.09831](http://arxiv.org/pdf/1907.09831)

