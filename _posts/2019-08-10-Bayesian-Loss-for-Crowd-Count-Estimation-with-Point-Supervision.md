---
layout: post
title: "Bayesian Loss for Crowd Count Estimation with Point Supervision"
date: 2019-08-10 04:01:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Zhiheng Ma, Xing Wei, Xiaopeng Hong, Yihong Gong
mathjax: true
---

* content
{:toc}

##### Abstract
In crowd counting datasets, each person is annotated by a point, which is usually the center of the head. And the task is to estimate the total count in a crowd scene. Most of the state-of-the-art methods are based on density map estimation, which convert the sparse point annotations into a "ground truth" density map through a Gaussian kernel, and then use it as the learning target to train a density map estimator. However, such a "ground-truth" density map is imperfect due to occlusions, perspective effects, variations in object shapes, etc. On the contrary, we propose \emph{Bayesian loss}, a novel loss function which constructs a density contribution probability model from the point annotations. Instead of constraining the value at every pixel in the density map, the proposed training loss adopts a more reliable supervision on the count expectation at each annotated point. Without bells and whistles, the loss function makes substantial improvements over the baseline loss on all tested datasets. Moreover, our proposed loss function equipped with a standard backbone network, without using any external detectors or multi-scale architectures, plays favourably against the state of the arts. Our method outperforms previous best approaches by a large margin on the latest and largest UCF-QNRF dataset. The source code is available at \url{this https URL}.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03684](https://arxiv.org/abs/1908.03684)

##### PDF
[https://arxiv.org/pdf/1908.03684](https://arxiv.org/pdf/1908.03684)

