---
layout: post
title: "Multigrid Predictive Filter Flow for Unsupervised Learning on Videos"
date: 2019-04-02 22:41:48
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Prediction
author: Shu Kong, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce multigrid Predictive Filter Flow (mgPFF), a framework for unsupervised learning on videos. The mgPFF takes as input a pair of frames and outputs per-pixel filters to warp one frame to the other. Compared to optical flow used for warping frames, mgPFF is more powerful in modeling sub-pixel movement and dealing with corruption (e.g., motion blur). We develop a multigrid coarse-to-fine modeling strategy that avoids the requirement of learning large filters to capture large displacement. This allows us to train an extremely compact model (4.6MB) which operates in a progressive way over multiple resolutions with shared weights. We train mgPFF on unsupervised, free-form videos and show that mgPFF is able to not only estimate long-range flow for frame reconstruction and detect video shot transitions, but also readily amendable for video object segmentation and pose tracking, where it substantially outperforms the published state-of-the-art without bells and whistles. Moreover, owing to mgPFF's nature of per-pixel filter prediction, we have the unique opportunity to visualize how each pixel is evolving during solving these tasks, thus gaining better interpretability.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01693](https://arxiv.org/abs/1904.01693)

##### PDF
[https://arxiv.org/pdf/1904.01693](https://arxiv.org/pdf/1904.01693)

