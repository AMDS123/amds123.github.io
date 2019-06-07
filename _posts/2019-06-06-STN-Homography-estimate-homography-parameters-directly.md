---
layout: post
title: "STN-Homography: estimate homography parameters directly"
date: 2019-06-06 12:07:22
categories: arXiv_CV
tags: arXiv_CV
author: Qiang Zhou, Xin Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce the STN-Homography model to directly estimate the homography matrix between image pair. Different most CNN-based homography estimation methods which use an alternative 4-point homography parameterization, we use prove that, after coordinate normalization, the variance of elements of coordinate normalized $3\times3$ homography matrix is very small and suitable to be regressed well with CNN. Based on proposed STN-Homography, we use a hierarchical architecture which stacks several STN-Homography models and successively reduce the estimation error. Effectiveness of the proposed method is shown through experiments on MSCOCO dataset, in which it significantly outperforms the state-of-the-art. The average processing time of our hierarchical STN-Homography with 1 stage is only 4.87 ms on the GPU, and the processing time for hierarchical STN-Homography with 3 stages is 17.85 ms. The code will soon be open sourced.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02539](http://arxiv.org/abs/1906.02539)

##### PDF
[http://arxiv.org/pdf/1906.02539](http://arxiv.org/pdf/1906.02539)

