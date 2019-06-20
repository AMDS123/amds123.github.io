---
layout: post
title: "Key Instance Selection for Unsupervised Video Object Segmentation"
date: 2019-06-18 23:49:22
categories: arXiv_AI
tags: arXiv_AI Salient Segmentation
author: Donghyeon Cho, Sungeun Hong, Sungil Kang, Jiwon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes key instance selection based on video saliency covering objectness and dynamics for unsupervised video object segmentation (UVOS). Our method takes frames sequentially and extracts object proposals with corresponding masks for each frame. We link objects according to their similarity until the M-th frame and then assign them unique IDs (i.e., instances). Similarity measure takes into account multiple properties such as ReID descriptor, expected trajectory, and semantic co-segmentation result. After M-th frame, we select K IDs based on video saliency and frequency of appearance; then only these key IDs are tracked through the remaining frames. Thanks to these technical contributions, our results are ranked third on the leaderboard of UVOS DAVIS challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07851](http://arxiv.org/abs/1906.07851)

##### PDF
[http://arxiv.org/pdf/1906.07851](http://arxiv.org/pdf/1906.07851)

