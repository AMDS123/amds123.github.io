---
layout: post
title: "Robust Monocular SLAM for Egocentric Videos"
date: 2018-11-17 20:00:08
categories: arXiv_CV
tags: arXiv_CV Quantitative SLAM
author: Suvam Patra, Kartikeya Gupta, Faran Ahmad, Chetan Arora, Subhashis Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
Regardless of the tremendous progress, a truly general purpose pipeline for Simultaneous Localization and Mapping (SLAM) remains a challenge. We investigate the reported failure of state of the art (SOTA) SLAM techniques on egocentric videos. We find that the dominant 3D rotations, low parallax between successive frames, and primarily forward motion in egocentric videos are the most common causes of failures. The incremental nature of SOTA SLAM, in the presence of unreliable pose and 3D estimates in egocentric videos, with no opportunities for global loop closures, generates drifts and leads to the eventual failures of such techniques. Taking inspiration from batch mode Structure from Motion (SFM) techniques, we propose to solve SLAM as an SFM problem over the sliding temporal windows. This makes the problem well constrained. Further, we propose to initialize the camera poses using 2D rotation averaging, followed by translation averaging before structure estimation using bundle adjustment. This helps in stabilizing the camera poses when 3D estimates are not reliable. We show that the proposed SLAM technique, incorporating the two key ideas works successfully for long, shaky egocentric videos where other SOTA techniques have been reported to fail. Qualitative and quantitative comparisons on publicly available egocentric video datasets validate our results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1707.05564](http://arxiv.org/abs/1707.05564)

##### PDF
[http://arxiv.org/pdf/1707.05564](http://arxiv.org/pdf/1707.05564)

