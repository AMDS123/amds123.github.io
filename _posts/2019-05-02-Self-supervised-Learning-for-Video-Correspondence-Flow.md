---
layout: post
title: "Self-supervised Learning for Video Correspondence Flow"
date: 2019-05-02 17:45:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Embedding
author: Zihang Lai, Weidi Xie
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this paper is self-supervised learning of feature embeddings from videos, suitable for correspondence flow, i.e. matching correspondences between frames over the video. We leverage the natural spatial-temporal coherence of appearance in videos, to create a "pointer" model that learns to reconstruct a target frame by copying colors from a reference frame. 
 We make three contributions: First, we introduce a simple information bottleneck that enforces the model to learn robust features for correspondence matching, and avoids it learning trivial solutions, e.g. matching based on low-level color information. Second, we propose to train the model over a long temporal window in videos. To make the model more robust to complex object deformation, occlusion, i.e. the problem of tracker drifting, we formulate a recursive model, trained with scheduled sampling and cycle consistency. Third, we evaluate the approach by first training on the Kinetics dataset using self-supervised learning, and then directly applied for DAVIS video segmentation and JHMDB keypoint tracking. On both tasks, our approach has achieved state-of-the-art performance, especially on segmentation, we outperform all previous methods by a significant margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00875](http://arxiv.org/abs/1905.00875)

##### PDF
[http://arxiv.org/pdf/1905.00875](http://arxiv.org/pdf/1905.00875)

