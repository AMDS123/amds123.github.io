---
layout: post
title: "Panoramic Robust PCA for Foreground-Background Separation on Noisy, Free-Motion Camera Video"
date: 2019-01-03 18:59:20
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Brian E. Moore, Chen Gao, Raj Rao Nadakuditi
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a new robust PCA method for foreground-background separation on freely moving camera video with possible dense and sparse corruptions. Our proposed method registers the frames of the corrupted video and then encodes the varying perspective arising from camera motion as missing data in a global model. This formulation allows our algorithm to produce a panoramic background component that automatically stitches together corrupted data from partially overlapping frames to reconstruct the full field of view. We model the registered video as the sum of a low-rank component that captures the background, a smooth component that captures the dynamic foreground of the scene, and a sparse component that isolates possible outliers and other sparse corruptions in the video. The low-rank portion of our model is based on a recent low-rank matrix estimator (OptShrink) that has been shown to yield superior low-rank subspace estimates in practice. To estimate the smooth foreground component of our model, we use a weighted total variation framework that enables our method to reliably decouple the true foreground of the video from sparse corruptions. We perform extensive numerical experiments on both static and moving camera video subject to a variety of dense and sparse corruptions. Our experiments demonstrate the state-of-the-art performance of our proposed method compared to existing methods both in terms of foreground and background estimation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.06229](http://arxiv.org/abs/1712.06229)

##### PDF
[http://arxiv.org/pdf/1712.06229](http://arxiv.org/pdf/1712.06229)

