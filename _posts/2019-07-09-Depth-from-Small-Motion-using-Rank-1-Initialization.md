---
layout: post
title: "Depth from Small Motion using Rank-1 Initialization"
date: 2019-07-09 09:50:04
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Peter O. Fasogbon
mathjax: true
---

* content
{:toc}

##### Abstract
Depth from Small Motion (DfSM) (Ha et al., 2016) is particularly interesting for commercial handheld devices because it allows the possibility to get depth information with minimal user effort and cooperation. Due to speed and memory issue on these devices, the self calibration optimization of the method using Bundle Adjustment (BA) need as little as 10-15 images. Therefore, the optimization tends to take many iterations to converge or may not converge at all in some cases. This work propose a robust initialization for the bundle adjustment using the rank-1 factorization method (Tomasi and Kanade, 1992), (Aguiar and Moura, 1999a). We create a constraint matrix that is rank-1 in a noiseless situation, then use SVD to compute the inverse depth values and the camera motion. We only need about quarter fraction of the bundle adjustment iteration to converge. We also propose grided feature extraction technique so that only important and small features are tracked all over the image frames. This also ensure speedup in the full execution time on the mobile device. For the experiments, we have documented the execution time with the proposed Rank-1 initialization on two mobile device platforms using optimized accelerations with CPU-GPU co-processing. The combination of Rank 1-BA generates more robust depth-map and is significantly faster than using BA alone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04058](http://arxiv.org/abs/1907.04058)

##### PDF
[http://arxiv.org/pdf/1907.04058](http://arxiv.org/pdf/1907.04058)

