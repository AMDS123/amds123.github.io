---
layout: post
title: "Detection of Moving Object in Dynamic Background Using Gaussian Max-Pooling and Segmentation Constrained RPCA"
date: 2017-09-03 03:38:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Inference Detection
author: Yang Li, Guangcan Liu, Shengyong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Due to its efficiency and stability, Robust Principal Component Analysis (RPCA) has been emerging as a promising tool for moving object detection. Unfortunately, existing RPCA based methods assume static or quasi-static background, and thereby they may have trouble in coping with the background scenes that exhibit a persistent dynamic behavior. In this work, we shall introduce two techniques to fill in the gap. First, instead of using the raw pixel-value as features that are brittle in the presence of dynamic background, we devise a so-called Gaussian max-pooling operator to estimate a "stable-value" for each pixel. Those stable-values are robust to various background changes and can therefore distinguish effectively the foreground objects from the background. Then, to obtain more accurate results, we further propose a Segmentation Constrained RPCA (SC-RPCA) model, which incorporates the temporal and spatial continuity in images into RPCA. The inference process of SC-RPCA is a group sparsity constrained nuclear norm minimization problem, which is convex and easy to solve. Experimental results on seven videos from the CDCNET 2014 database show the superior performance of the proposed method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.00657](https://arxiv.org/abs/1709.00657)

##### PDF
[https://arxiv.org/pdf/1709.00657](https://arxiv.org/pdf/1709.00657)

