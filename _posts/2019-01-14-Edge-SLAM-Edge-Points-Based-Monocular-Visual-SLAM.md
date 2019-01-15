---
layout: post
title: "Edge SLAM: Edge Points Based Monocular Visual SLAM"
date: 2019-01-14 09:40:45
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Optimization SLAM Relation
author: Soumyadip Maity, Arindam Saha, Brojeshwar Bhowmick
mathjax: true
---

* content
{:toc}

##### Abstract
Visual SLAM shows significant progress in recent years due to high attention from vision community but still, challenges remain for low-textured environments. Feature based visual SLAMs do not produce reliable camera and structure estimates due to insufficient features in a low-textured environment. Moreover, existing visual SLAMs produce partial reconstruction when the number of 3D-2D correspondences is insufficient for incremental camera estimation using bundle adjustment. This paper presents Edge SLAM, a feature based monocular visual SLAM which mitigates the above mentioned problems. Our proposed Edge SLAM pipeline detects edge points from images and tracks those using optical flow for point correspondence. We further refine these point correspondences using geometrical relationship among three views. Owing to our edge-point tracking, we use a robust method for two-view initialization for bundle adjustment. Our proposed SLAM also identifies the potential situations where estimating a new camera into the existing reconstruction is becoming unreliable and we adopt a novel method to estimate the new camera reliably using a local optimization technique. We present an extensive evaluation of our proposed SLAM pipeline with most popular open datasets and compare with the state-of-the art. Experimental result indicates that our Edge SLAM is robust and works reliably well for both textured and less-textured environment in comparison to existing state-of-the-art SLAMs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.04210](http://arxiv.org/abs/1901.04210)

##### PDF
[http://arxiv.org/pdf/1901.04210](http://arxiv.org/pdf/1901.04210)

